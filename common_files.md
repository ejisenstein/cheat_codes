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

## Oh My Zsh short cuts
### 1. Open zsh
- vi ~/.zshrc

## Turn on Spelling Corrections for ZSH
### 2. setopt
- `setopt correct` turns on corrections
- `unsetopt correct` turns off corrections 

## Add/Remove Virtual Environments from Jupyter Notebooks
### 1. Add virtual env (venv)
- activate venv
- ensure ipykernel is installed `pip install --user ipykernel`
- set venv through this code `python -m ipykernel install --name=venv`
-This should print the following: 
--`Installed kernelspec myenv in /home/user/.local/share/jupyter/kernels/myenv`

### 2. Uninstall the kernel
- List available kernels with `jupyter kernelspec list`
- Uninstall kernel with `jupyter kernelspec uninstall myenv`
