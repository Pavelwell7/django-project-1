# Bank security console

This is the internal repository of the bank "We will take your money". If you got here by accident, then you do not have access to the database, but you can view and use the layout code.

### How to install

The project uses the following settings:

 `DJANGO_SETTINGS_MODULE` - specifies the path to the module with Django settings.

 To work with the database, you need to configure the appropriate parameters in the `settings.py` file.

 Necessary environment variables `settings.py` file.

 Before running the program, you need to set the following environment variables:

 `DB_ENGINE` - database engine (for example: django.db.backends.postgresql)

 `DB_HOST` - database host.

 `DB_PORT` - port for connecting to the database.

 `DB_NAME` - database name.

 `DB_USER` - database user.

 `DB_PASSWORD` - password for connecting to the database.

Python3 should be already installed. 
Then use `pip` (or `pip3`, if there is a conflict with Python2) to install dependencies:
```
pip install -r requirements.txt
```

After installing the dependencies, run the script.
```
python main.py
```

### Project Goals

The code is written for educational purposes on online-course for web-developers [dvmn.org](https://dvmn.org/).
