# Flask Quickstart With Database And Flask Admin

The Quickstart project provide a quick setup to a dummy project that has a database and an admin panel. This project only gives bare minimum code required to get started.

For other quickstart projects, refer to the following projects:

* [Flask Quickstart] (https://github.com/eguru/flask-quickstart)
* [Flask Quickstart With Database] (https://github.com/eguru/flask-quickstart-database)
* [Flask Quickstart With SSL] (https://github.com/eguru/flask-quickstart-ssl)

# Installation

First, simply get a copy of the project:

```
git clone https://github.com/eguru/flask-quickstart-database-admin.git
```

Now, create a virtual environment, see virtualenv installation [here] (https://virtualenv.pypa.io/en/stable/installation/):

```
cd flask-quickstart-database-admin/
virtualenv venv
```

Activate the virtual environment:

```
source venv/bin/activate
```

Install the Flask framework:

```
pip install flask
```

Install the Flask's SQLAlchemy extension:

```
pip install flask_sqlalchemy
```

Install the Flask's Admin extension:

```
pip install flask_admin
```

Now, simply start the server:

```
python server.py
```

Open up your web browser and enter the following location:

```
http://localhost:8080
```

Access the admin panel from the following location:
```
http://localhost:8080/admin
```

