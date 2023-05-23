# Data Engineering Challenge 2023
Setup and sample datasets for the final round of the challenge

### Setup
Download the repo as zip and extract or clone it to your laptop. There are the subfolders and their content:
- `win_x64/` binary for Windows 64 bit
- `linux_x64/` binary for Linux 64 bit
- `linux_arm64/` binary for Linux ARM 64
- `mac_osx/` binary for Mac OSX 
- We could not provide the binary for MAc OSX as it was too large for Github to store. Please download it from https://github.com/duckdb/duckdb/releases/download/v0.8.0/duckdb_cli-osx-universal.zip
- `data/` sample datasets
- More information on DuckDB at https://duckdb.org/docs/

### Uses
- Open the DB: `<platform>/duckdb database.duckdb`. 
- The file `database.duckdb` is the embedded database where we have already defined the views using the datasets from `data/` directory.
- See all tables: `show tables;`
- Sample SQL: `SELECT * FROM nation LIMIT 10;`
- DuckDb help & options: `.help`
- Exit DuckDb: `.exit`
- If required, add execute permission to the Linux/Mac binary: `chmod u+x <platform>/duckdb`
- In the repo you will find a file `README.png` which has the ER diagram of the dataset
- On windows use `duckdb.exe ` for the command in (a)
