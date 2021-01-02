# rumah-kita
Rumah Kita: Home away from home
https://github.com/ingafter60/rumah-kita


## 1. SETUP 

### 1. Create github repository

### 2. Pushing the local repo to github


## 2. DJANGO PROJECT

### 1. Create django project 'config' inside root folder

        modified:   README.md
        new file:   config/__init__.py
        new file:   config/asgi.py
        new file:   config/settings.py
        new file:   config/urls.py
        new file:   config/wsgi.py
        new file:   manage.py

### 2. Create 6 django apps: conversations, lists, reservations, reviews, rooms, and users

### 3. Modified README.md file


## 3.1 USER APP - TRIAL 

### 3.1.0 Use default sqlite db and run migrations

### 3.1.1 Create superuser

        modified:   README.md
        deleted:    config/asgi.py
        modified:   config/settings.py
        modified:   config/urls.py
        modified:   config/wsgi.py
        modified:   manage.py

## 3.2 USER APP - SETTING UP POSTGRESQL AS THE DATABASE

### 3.2.0 Replacing Default User 

### 3.2.1 Introduction to the User Model

        modified:   README.md
        modified:   config/settings.py
        modified:   users/admin.py
        modified:   users/models.py
        users/migrations/0001_initial.py
        users/migrations/0002_user_bio.py

### 3.3 Setup DB and Modify settings.py     
  
        modified:   Pipfile
        modified:   Pipfile.lock
        modified:   README.md
        modified:   config/settings.py
        modified:   users/admin.py