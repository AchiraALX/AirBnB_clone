# This is the ALX AirBnB clone project repository

<img src="https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2018/6/65f4a1dd9c51265f49d0.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20230213%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20230213T012256Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=644bcc86dbf82ecc620edfe18bbce4199eaf839cbd549d8df6f82c6b4ebfed81" />

## Description

This repository contains the AirBnB clone project, which is the first step towards building a full web application. The goal of this project is to deploy on your server a simple copy of the AirBnB website.

## Environment

* Files will be interpreted/compiled on Ubuntu 14.04 LTS using python3 (version 3.4.3)
* Code should use the PEP 8 style (version 1.7.*)
* All files must be executable
* The first line of all your files should be exactly #!/usr/bin/python3
* The length of your files will be tested using wc

## Usage

The console works both in interactive mode and non-interactive mode, much like a Unix shell.
It prints a prompt **(hbnb)** and waits for the user for input.

Command | Example
------- | -------
Run the console | ```./console.py```
Quit the console | ```(hbnb) quit```
Display the help for a command | ```(hbnb) help <command>```
Create an object (prints its id)| ```(hbnb) create <class>```
Show an object | ```(hbnb) show <class> <id>``` or ```(hbnb) <class>.show(<id>)```
Destroy an object | ```(hbnb) destroy <class> <id>``` or ```(hbnb) <class>.destroy(<id>)```
Show all objects, or all instances of a class | ```(hbnb) all``` or ```(hbnb) all <class>```
Update an attribute of an object | ```(hbnb) update <class> <id> <attribute name> "<attribute value>"``` or ```(hbnb) <class>.update(<id>, <attribute name>, "<attribute value>")```

### Interactive mode (example)

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

### Non-interactive mode (example)

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

* **Jacob Achira**
* **Umar Murtala**
