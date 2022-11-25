# AirBnB Clone Project
![AirBnb Clone](Screenshot_20221125_070856.png)

# Project Description

The goal of this project is to create a complete website application which is composed of:

- A command interpreter to manipulate data without a visual interface, like in a Shell (perfect for development and debugging)

- A website (the front-end) that shows the final product to everybody: static and dynamic

- A database or files that store data (data = objects)

- An API that provides a communication interface between the front-end and your data (retrieve, create, delete, update them)

# Description of the command interpreter:
This is exactly the same as the Bash shell but limited to a specific use-case solely defined for the purposes of the usage of the AirBnB website. In this case, we want to be able to manage the objects of our project:

This command line interpreter serve as alternative to frontend where user can interact with the backend which was developed using the Python Objects-Oriented Programming

Thus, the following action can be performed;

- Create a new object (ex: a new User or a new Place)

- Retrieve an object from a file, a database etc…

- Do operations on objects (count, compute stats, etc…)

- Update attributes of an object

- Destroy an object

# How to start interact
This instruction will guide you on how to get this project up and running on your local machine for development and testing purposes

# Installing
You will need to clone the repository of the project from Github. This will contain the command line program and all of its dependencies.



# Installation

You will need to clone the repository of the project from Github. This will contain the command line program and all of its dependencies.

```bash
  https://github.com/StephainG/AirBnB_clone.git
```

After cloning this repository, you would have a folder named AirBnB_clone which contains all the files needed for this program to work

/console.py : The main executable of the project, the command interpreter.

models/engine/file_storage.py: Class that serializes instances to a JSON file and deserializes JSON file to instances

models/__ init __.py: A unique FileStorage instance for the application

models/base_model.py: Class that defines all common attributes/methods for other classes.

models/user.py: User class that inherits from BaseModel

models/state.py: State class that inherits from BaseModel

models/city.py: City class that inherits from BaseModel

models/amenity.py: Amenity class that inherits from BaseModel

models/place.py: Place class that inherits from BaseModel

models/review.py: Review class that inherits from BaseModel

# How to use it

It can work in two different mode, both interactive and non-interactive mode

In interactive mode, the console will display a prompt(hbnb) asking the user to write something for execution and which it continues as long as the user keeps interacting with it.

```bash
  $ ./console.py
(hbnb) help

Documented commands (type help <topic>):
========================================
EOF  help  quit

(hbnb) 
(hbnb) 
(hbnb) quit
$
```

In non-interactive mode, no prompt will appear in this case as the command inputted will run as soon as the shell starts.

```bash
$ echo "help" | ./console.py
(hbnb)

Documented commands (type help <topic>):
========================================
EOF  help  quit
(hbnb) 
$
$ cat test_help
help
$
$ cat test_help | ./console.py
(hbnb)

Documented commands (type help <topic>):
========================================
EOF  help  quit
(hbnb) 
$
```



## Authors

- [@StephainG](https://www.github.com/StephainG)
- [@Image101](https://www.github.com/Image101)
