0x00 AirBnB clone | The Console

## 0x00.Table of content

* [0x01 Introduction](#0x01-introduction)
* [0x02 Environment](#0x02-Environment)
* [0x03 Installation](#0x03-Installation)
* [0x04 Testing](#0x04-Testing)
* [0x05 Usage](#0x05-Usage)
* [0x06 Authors](#0x06-Authors)

## 0x01 Introduction
Team project to build a clone of [AirBnB](https://www.airbnb.com/).

The console is a command interpreter to manage objects abstraction between objects and how they are stored.

To see the fundamentals background of the project visit the [wiki](https://github.com/stormshadow96/AirBnB_clone/wiki).

The console will perform the following tasks:

* Create a new object
* Retrive an object from a file
* Do operations on object
* Destroy an object

### Storage

All the classes are handled by the 'Storage' engine in the 'FileStorage' Class.

## 0x02 Environment

* Style guidelines:
* [pycodestyle] (version 2.7.*)(https://pypi.org/project/pycodestyle/)
* [PEP8](https://pep8.org/)

All the development and testing was runned over an operating system Ubuntu 20.04 LTS using programming language Python 3.8.3. The editors used were VIM 8.1.2269, VSCode 1.6.1 and Atom 1.58.0 . Control version using Git 2.25.1.

##0x03 Installation

'''bash
git clone https://github.com/stormshadow96/AirBnb_clone.git
'''

change to the 'AirBnb' directory and run the command:

'''bash
$ ./console.py
(hbnb) help

### Execution

In interactive mode

'''bash
$ ./console.py
(hbnb) help

Documented commands (type help <topic>):
========================================
EOF  help  quit

(hbnb)
(hbnb)
(hbnb) quit
$
'''

in Non-interactive mode

'''bash
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
