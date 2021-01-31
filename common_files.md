# Commonly used Codes

## Initial Setup
### 1. Create a Virtual Environment in a New Directory
A new virtual environment is necessary for. You can use
whatever virtual environment you prefer, I typically use venv
- First create a new directory: `mkdir <dir_name>`
- Create a new environment `python3 -m venv <env_name>`
- Activate the new environment `source <env_name>/bin/activate`

## Create DB
### 2. Create a DB within the project directory
use the db create all function to build the database
For for SQL Alchemy pip install flask-sqlalchemy
- Navigate to the project folder: `cd filename`
- Initialize python `python`
- Import db from directory `from filename import db`
- Init DB `db.create_all()`
