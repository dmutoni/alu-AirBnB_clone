# AirBnB clone - The console


# Description of the project

This project is a basic version of the AirBnB website. The first stage builds a backend interface or console for managing program data (similar to a command-line shell). Users can use console commands to create, update, delete objects, and handle file storage.

# The console - tasks
- The parent class, **BaseModel**, will handle setting up, converting to, and restoring from different formats for future objects.
- Set up a simple process for converting objects: **Instance <-> Dictionary <-> JSON string <-> file**.
- Make all the classes for AirBnB (like **User**, **State**, **City**, **Place**, etc.) and make sure they inherit from **BaseModel**.
- Build the first storage system for the project: **File storage**.
- Write unit tests to make sure all classes and the storage system work correctly.


# Description of the command interpreter

The command interpreter helps us to manage the objects of our project by:

- Creating a new object (ex: a new User or a new Place)
- Retrieving an object from a file, a database etc…
- Doing operations on objects (count, compute stats, etc…)
- Updating attributes of an object
- Destroying an object

## How to start the interpreter

```bash
./console.py
(hbnb) help

Documented commands (type help <topic>):
========================================
EOF  all  create  delete  destroy  exit  help  q  quit  show  update

(hbnb) 
(hbnb) 
(hbnb) quit

```

## How to use the interpreter

## Tests
To run all the tests execute the following command:

```bash
$ python3 -m unittest discover tests
```
You can also run a single test by specifying the test file:

```bash
$ python3 -m unittest tests/test_models/test_city.py

```


# Authors

## [`Denyse Mutoni Uwingeneye`](https://www.linkedin.com/in/denyse-mutoni-23790918a/)
## [`Sage Muhodari`](https://rw.linkedin.com/in/sage-muhodari-936918185)
