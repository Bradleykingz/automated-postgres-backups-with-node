# Automated Backups with Postgres and NodeJS

This project is an overview of how to use `pg_dump` and `cron` to 
automate backing up a Postgres database and sending it to a remote location.

It is composed of two files - `backup-database.js` and `index.js`. All relevant
methods are contained in the former file, which only exposes a single method.

In order to get the project to work, create a `.env` file and enter the following details

```.env
DB_NAME=<your database name>
DB_USER=<your postgres username>
PGPASS=<your postgres password>
```