## Django
---
- Create A New Django Project
```bash
 django-admin startproject <ProjectName>
```
- Run Django Project
```bash
 python3 manage.py runserver
```
- Create new App
```bash
 python3 manage.py startapp <AppName>
```
- Migrate / Create Database
```bash
  python3 manage.py migrate
```
- Make migration tells to the that we have made some changes in models.
```bash
 python3 manage.py makemigrations <AppName>
```
- For create tables we have to run sqlmigarte command.
```bash
	python3 manage.py sqlmigarte <AppName> <MigrationId> 
```  
- For run interative python shell
```bash
	python3 manage.py shell
```