# Flasky

Flask project based on the O'Reilly book "Flask Web Development" by Miguel Grinberg



## First step: Virtual environments

**Install your virtual environment**

This project is based on Python 3 and uses virtual environments. Since virtual environments by the .gitignore file, you have to create it yourself.
If you are on a **Ubuntu** system, you probably have to install it first: ```sudo apt-get install python3-venv```

The command that creates a virtual environment has the following structure:

```$ python3 -m venv virtual-environment-name```

The following commoand will create the venv folder in your current directory:

```$ python3 -m venv venv```

**Activate your virtual environment**

If everything worked so far, you have to actually active your virtual environment in order to use it and install packages:

```$ python3 -m venv venv```

Hopefully this will result into the following prompt in your terminal:

```(venv) $```

**Install flask in your virtual environment**

You can install flask by executing the following command:

```(venv) $ pip install flask```

If you are curious about the packages that flask additionally installed, you can check that by using pip freeze:

```
(venv) $pip freeze

click==7.1.2
Flask==1.1.2
itsdangerous==1.1.0
Jinja2==2.11.2
MarkupSafe==1.1.1
Werkzeug==1.0.1
```

**Check Flask installation**

You can check if the flask installation was successful by executing:

```
(venv) $ python
>>> import flask
>>>
```


