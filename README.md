AirBnB Clone ― The ALX-Holberton BnB

hbnb



Description of the project

The ALX-Holberton B&B sums up the implementation of my four months of studies at the ALX-Holberton School - the fullstack software engineering program. The goal of the project is to deploy a replica of the Airbnb Website using my server. The final version of this project will have:



1. A command interpreter to manipulate data without a visual interface, like a shell (for development and debugging)

2. A website (front-end) with static and dynamic functionalities

3. A comprehensive database to manage the backend functionalities

4. An API that provides a communication interface between the front and backend of the system.

5. General concepts in review



As you navigate this code base, it is great to note the following concepts, while completing this project;

How to create a Python package

How to create a command interpreter in Python using the cmd module

What is Unit testing and how to implement it in a large project

How to serialize and deserialize a Class

How to write and read a JSON file

How to manage datetime

What is an UUID

What is *args and how to use it

What is **kwargs and how to use it

How to handle named arguments in a function

Environment 💻

The console was developed in Ubuntu 14.04LTS using python3 (version 3.4.3).



Further information 📑

For further information on python version, and documentation visit python.org.



Requirements 📝

Knowledge in python3, how to use a command line interpreter, a computer with Ubuntu 14.04, python3 and pep8 style corrector.



Repo Contents 📋

This repository constains the following files:



File	Description

AUTHORS	Contains info about authors of the project

base_model.py	Defines BaseModel class (parent class), and methods

user.py	Defines subclass User

amenity.py	Defines subclass Amenity

city.py	Defines subclass City

place.py	Defines subclass Place

review.py	Defines subclass Review

state.py	Defines subclass State

file_storage.py	Creates new instance of class, serializes and deserializes data

console.py	creates object, retrieves object from file, does operations on objects, updates attributes of object and destroys object

test_base_model.py	unittests for base_model

test_user.py	unittests for user

test_amenity.py	unittests for amenity

test_city.py	unittests for city

test_place.py	unittests for place

test_review.py	unittests for review

test_state.py	unittests for state

test_file_storage.py	unittests for file_storage

test_console.py	unittests for console

Installation 🛠️

Clone the repository and run the console.py



$ git clone https://github.com/------/AirBnB_clone.git

Usage 🔧

Method	Description

create	Creates object of given class

show	Prints the string representation of an instance based on the class name and id

all	Prints all string representation of all instances based or not on the class name

update	Updates an instance based on the class name and id by adding or updating attribute (save the change into the JSON file)

destroy	Deletes an instance based on the class name and id (save the change into the JSON file)

count	Retrieve the number of instances of a class

help	Prints information about specific command

quit/ EOF	Exit the programPricing
