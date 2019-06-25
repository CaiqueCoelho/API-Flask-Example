pip3 install Flask
pip3 install flask_sqlalchemy
pip3 install flask_marshmallow
pip3 install marshmallow-sqlalchemy

1. enter into python interactive shell

First you need to enter into python interactive shell using following command in your terminal:

$ python

2. import db object and generate SQLite database

Use following code in python interactive shell

>>> from crud import db
>>> db.create_all()