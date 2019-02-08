# Drupal Migration

A SampleCSV is provided which serves as a template for creating CSV files for data migration.
You need to provide the path of the CSV file in migration.yml file.

## How to use?
There are 2 sub-modules, one for content-type import and the other one is for data import using migration.
First, install content-type module and then the migration.

### Installation
* Go to 'Extend'. Search by the module name. Do the installation.
* Then, go to 'Structure'->'Migrations'.
* Click on 'List migrations'. The migration module will be listed by the name provided in the 'id' field.
* Click on 'Execute' button against the module.
* Choose operation to run as 'Import' and then, click on 'Execute'.
* Thus, the migration is successfully imported.
* You can check this by filtering content-type.
