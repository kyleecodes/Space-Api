# Space API 🚀

A fullstack RESTful API project featuring a Flask backend, React frontend, and Postgres! Add, delete, and search questions about outerspace. 🚀

Backend additional features: SQLAlchemy and Flask Cors

Frontend additional features: JQuery

## Installation
### Backend:
 First, cd into the backend directory.

Now create the database:
```
 createdb spacetrivia
```
 
Populate the database:
```
 psql spacetrivia < spacetrivia.psql
```

#### In another terminal, let's get the flask server running!

It is highly recommended that you run this in a virtualenv in order to keep your dependency, read about how to do this [here](https://docs.python.org/3/library/venv.html) on your own local machine.

Next, enter your psql credientals in the database_path in models.py:
```
user = ""
pwd = ""
```

Then, pip install requirements: 
```
pip install -r requirements.txt
```

Finally, let's run the flask server:
```
export(for Unix/Mac) or set (for Windows) FLASK_APP=flaskr
export FLASK_ENV=development
flask run
```

### Frontend:
Now, cd into the frontend directory.

Next, run your necessary npm commands:
```
npm install
npm start
```

#### Now you should see the project live at [http://localhost:3000](http://localhost:3000)

## API Documentation

##### *This API follows RESTful conventions*

### TODO:
- [ ] API documentation
- [ ] input question validation
- [ ] comment code
- [ ] fix category naming conventions
