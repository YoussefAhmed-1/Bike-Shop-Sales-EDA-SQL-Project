# SQL Data Analytics Project for bike shop & online

```
sql-data-analytics-project/
├── 00_setup/                        the setup guide, and the one-click Docker start for Mac
├── 01_datasets/                     the data, as a backup and as CSV files
│   ├── DataWarehouseAnalytics.bak   the database, ready to restore
│   └── csv-files/                   the same data, to build the database yourself
├── 02_docs/                         the project roadmap and notes
└── 03_scripts/                      the queries, in the order of the videos
    └── 00_init_database.sql         builds the database from the CSV files
```
Get the database in one of two ways:

- Restore `01_datasets/DataWarehouseAnalytics.bak` in SSMS. It needs SQL Server 2022 or newer.
- Or run `03_scripts/00_init_database.sql`. It builds the database from the CSV files in `C:\sql\sql-data-analytics-project\01_datasets\csv-files\`.
