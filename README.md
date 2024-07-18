# WebGis Application using GeoDjango Framework 

Geodjango project parctice for PKP aunty pita. 2024

# Daftar Isi
- [Installation](#installation)

## Installation

Create Virtual Enviroment for Django
 ```terminal
 #to install virtual enviroment for python
 sudo apt install python-virtualenv

 #create virtual env folder
 virtualenv <nama folder env> atau python -m venv <nama folder> 

 #enable virtual env
 source <nama folder env>/bin/activate
```

 Install pip
 ```bash
 sudo apt install python-pip
 ```

 Install django project
 ```bash
 #install django
 pip install django
 #check django installation
 python -m django --version
 ```
Membuat Project Django
```bash
django-admin startproject <nama project>
```
Running django
```bash
python manage.py runserver <ip public : port>
#note : use ip public if you want open in another computer browser
```

for more just read [documentation of django](https://docs.djangoproject.com/en/5.0/)





