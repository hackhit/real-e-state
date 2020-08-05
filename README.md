# Building a Real E-State Application

## Creating	an	isolated	Python environment

```console
pip install virtualenv
```
After you install virtualenv, create an isolated enviroment with the following command:

```console
virtualenv my_env
```
This	will	create	a	my_env/	directory,	including	your	Python environment.	Any	Python	libraries	you	install	while	your	virtual environment	is	active	will	go	into	the	
**my_env/
     lib/
      python3.6/
         site-packages directory.**


Create the virtualenv for Project  with following Command:

__for Windows User__

```console
python -m venv env 
```

__for Linux  User__

```console
python3 -m venv env 
```

Run	the	following	command	to	activate	your	virtual	environment:

__for Windows User__

```console
source	my_env/Scripts/Activate
```

__for Linux  User__

```console
source	my_env/bin/activate 
```
# Installing Django with pip

```console
pip install Django
```

Django will be installed in the Python site-packages/ directory of your environment

Now check whether Django has been successfully installed. Run **python** on a terminal, import Djnago, check its version, as follows:

```console
>>> import django
>>> djnago.get_version()
'3.0.1'

```

# Creating your Project:
---

Our first Django project will buillding a complete Real E-state. Django Provides a command that allow you to create an  initial project file struture.

Run the following command from your activate env terminal:

```bash
django-admin startproject mysite
```
This will create a Django Project with the name mysite.

#### Let's take a look at the project structure genrated:

```console
mysite/
     manage.py
     mysite/
          init__.py
          settings.py
          urls.py
          wsgi.py
```
