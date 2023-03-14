0x00. AirBnB clone - The console
This is the repository for the first part of the AirBnB clone project, which is a command line interface that interacts with a JSON file.

Table of Contents
Description
Installation
Usage
Commands
Authors
Description
This project is the first part of a larger project to create a clone of AirBnB, a web-based application for booking and renting accommodations. The purpose of this project is to create a command line interface that interacts with a JSON file to manage the creation, updating, and deletion of instances of various classes (e.g. User, Place, Review) that are part of the AirBnB data model. The command line interface supports CRUD (create, read, update, delete) operations for these instances, as well as search and filter operations.

The console is built with Python 3, and uses the cmd module to provide a shell-like interface for interacting with the JSON file. The JSON file is used as a simple database for storing instances of the different classes, and is updated as instances are created, updated, or deleted.

Installation
To use the console, you must have Python 3 installed on your system. You can download Python 3 from the official Python website: https://www.python.org/downloads/

Once you have Python 3 installed, you can clone this repository to your local machine using the following command:

bash
Copy code
git clone https://github.com/<username>/AirBnB_clone.git
Replace <username> with your GitHub username.

Usage
To start the console, navigate to the project directory and run the following command:

javascript
Copy code
./console.py
This will start the console and display a prompt that looks like this:

scss
Copy code
(hbnb) 
You can now enter commands at the prompt to interact with the JSON file.

Commands
The console supports the following commands:

Command	Syntax	Description
help	help [command]	Displays help information about a command.
quit	quit	Exits the console.
EOF	EOF	Exits the console.
create	create <class>	Creates a new instance of a class.
show	show <class> <id>	Displays information about an instance.
destroy	destroy <class> <id>	Deletes an instance.
all	all [class]	Displays information about all instances or all instances of a class.
update	update <class> <id> <attribute> "<value>"	Updates the value of an attribute of an instance.
count	count <class>	Counts the number of instances of a class.
emptyline	emptyline	Does nothing.

