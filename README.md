# Sunchronìzo lexikà!

[![Stato del repository: archiviato](https://img.shields.io/badge/stato-archiviato-inactive?style=for-the-badge)](https://github.com/ouitoulia/sunchronizo_lexika?style=for-the-badge)
![GitHub](https://img.shields.io/github/license/ouitoulia/sunchronizo_lexika?style=for-the-badge)
![GitHub release (latest SemVer)](https://img.shields.io/github/v/release/ouitoulia/sunchronizo_lexika?sort=semver&style=for-the-badge)
![Packagist Dependency Version](https://img.shields.io/packagist/dependency-v/ouitoulia/sunchronizo_lexika/drupal/core-recommended?style=for-the-badge)
![Packagist Downloads](https://img.shields.io/packagist/dt/ouitoulia/sunchronizo_lexika?style=for-the-badge)

> ⚠ **Questo repository è archiviato. Le funzionalità sono state spostate su `ouitoulia/sunchronizo`**

Sunchronìzo lexikà è un modulo Drupal che importa le voci di tassonomia utilizzate dalle scuole.
Questo modulo usa `drupal/migrate` per importare le voci presenti nel repository [Krène](https://github.com/ouitoulia/krene) 

## Requisiti
- Drupal: >= 10
- Profilo Drupal: `minimal`
- Moduli contrib: `migrate_plus`, `migrate_tools`
- Moduli Ouitoulìa: `lexika`

## Installazione
Per aggiungere e installare il modulo alla tua installazione esegui:
```bash
$ composer require ouitoulia/sunchronizo_lexika
$ drush -y en sunchronizo_lexika
```
Questo è il risultato

![Screenshot della lista delle migrazioni](docs/migrations.png "Screenshot della lista delle migrazioni")

## Uso del modulo
Puoi utilizzare il modulo:
- da interfaccia grafica;
- da CLI se hai bisogno di automatizzare l'installazione o l'aggiornamento.

In entrambi i casi, leggi la documentazione del modulo 
Drupal `migrate` per maggiori dettagli.

Di seguito un esempio delle voci importate nel vocabolario "Percorsi di studio"

![Screenshot della lista delle voci importate](docs/percorsi_di_studio.png "Screenshot della lista delle voci importate")

## License

Copyright (C) 2023 https://github.com/ouitoulia

This program is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License version 3 as published by the Free Software Foundation.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License for more details.

Questo è un software libero: puoi ridistribuirlo e/o modificarlo secondo i termini della GNU General Public License versione 3 pubblicata dalla Free Software Foundation.

Questo programma è distribuito nella speranza che possa essere utile, ma SENZA ALCUNA GARANZIA; senza nemmeno la garanzia implicita di COMMERCIABILITÀ o IDONEITÀ PER UNO SCOPO PARTICOLARE. Vedere la GNU General Public License per maggiori dettagli.