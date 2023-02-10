#Alx School - AirBnB_clone This project replicates the basic functionality of the Air BnB website.

Prerequisites:
All python files were written with Python-3.4.3 and conform to PEP 8 Styling

Install Fabric3:

pip3 uninstall Fabric
sudo apt-get install libffi-dev
sudo apt-get install libssl-dev
sudo apt-get install python3.4-dev
sudo apt-get install libpython3-dev
pip3 install pyparsing
pip3 install appdirs
pip3 install Fabric3
Usage:
Interactive Mode:

PROMPT~> ./console.py
(hbtn) help

Documented Commands (type help <topic>)
======================================
EOF   help   quit

(hbtn)
(hbtn)
(hbtn) quit
PROMPT~>
Non-Interactive Mode:

PROMPT~> echo "help" | ./console.py
(hbnb)

Documented commands (type help <topic>):
========================================
EOF  help  quit
(hbnb) 
PROMPT~> cat test_help
help
PROMPT~> cat test_help | ./console.py
(hbnb)

Documented commands (type help <topic>):
========================================
EOF  help  quit
(hbnb) 
PROMPT~> 
Description of Files
console.py
Main Command line user interface
models/
Directory that contains all the unit models
models/__init__.py
File that Initializes the Base Model
models/place.py
Create a set of public class attributes relating to the place requested.
models/city.py
Create a set of public class attributes relating to the city name and state id.
models/base_model.py
Base Model that contains everything all other classes will inherit from.
models/review.py
Create a set of public class attributes, relating to reviews of places and initializing a review class.
models/amenity.py
Create a set of public class attributes that enables each command to accept arguments
models/user.py
Create a set of public class attributes, about user information and initializing a new users.
models/state.py
Create a set of public class attributes, that define the state of the objects
models/engine/
Directory that contains main engines for file storage and persistent data.
models/engine/file_storage.py
Defines how a json object stores the values in the dictionary.
tests/
Unit tests of all functions
Helpful Links
Python Docs: Cmd
Python Docs: Modules / Packages
Python Docs: UUID
Python Docs: datetime
Python Docs: Unit test
Python Tips: args and kwargs
All about cmd
Give Python a shell
Authors:
Benjamin Olaniran <https://github.com/NomsuBen>
Yusuf Ridwan <https://github.com/Y-Ridwan>
