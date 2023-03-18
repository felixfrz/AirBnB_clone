# AirBnB_clone

**Authors:** *Surina Singh* and *Ayodeji Felix Oladoyin*

## Description

Write a command interpreter to manage your AirBnB objects.
This is the first step towards building a first full web application: the AirBnB clone.This first step consists of a custom command-line interface for data management, and the base classes for the storage of this data. This first step built is important for all other following projects: HTML/CSS templating, database storage, API, front-end integration…

---

## Resources

- [cmd module](https://<https://intranet.alxswe.com/rltoken/8ecCwE6veBmm3Nppw4hz5A>)
- [cmd module in depth](https://<https://intranet.alxswe.com/rltoken/uEy4RftSdKypoig9NFTvCg>)
- [packages concept page]
- [uuid module](https://<LINK>)
- [datetime](https://<LINK>)
- [unittest module](https://<LINK>)
- [args/kwargs](https://<LINK>)
- [Python test cheatsheet](https://<LINK>)
- [cmd module wiki page](https://<LINK>)
- [python unittest](https://<LINK>)

---

## General Requirements
* How to create a Python package
* How to create a command interpreter in Python using the cmd module
* What is Unit testing and how to implement it in a large project
* How to serialize and deserialize a Class
* How to write and read a JSON file
* How to manage datetime
* What is an UUID
* What is *args and how to use it
* What is **kwargs and how to use it
* How to handle named arguments in a function

---

## Tests

* All the test are defined in the `tests` folder.

---

### Documentation

* Modules:

```python
python3 -c 'print(__import__("my_module").__doc__)'
```

* Classes:

```python
python3 -c 'print(__import__("my_module").MyClass.__doc__)'
```

* Functions (inside and outside a class):

```python
python3 -c 'print(__import__("my_module").my_function.__doc__)'
```

and

```python
python3 -c 'print(__import__("my_module").MyClass.my_function.__doc__)'
```

### Python Unit Tests

* unittest module
* File extension ``` .py ```
* Files and folders star with ```test_```
* Organization:for ```models/base.py```, unit tests in: ```tests/test_models/test_base.py```
* Execution command: ```python3 -m unittest discover tests```
* or: ```python3 -m unittest tests/test_models/test_base.py```

### run test in interactive mode

```bash
echo "python3 -m unittest discover tests" | bash
```

### run test in non-interactive mode

To run the tests in non-interactive mode, and discover all the test, you can use the command:

```bash
python3 -m unittest discover tests
```
---

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

Non-interactive mode example

```bash
$ echo "help" | ./console.py
(hbnb)

Documented commands (type help <topic>):
========================================
EOF  all  count  create  destroy  help  quit  show  update
```
---

# Tasks

## Mandatory Tasks
### 0. README, AUTHORS
### 1. Be pycodestyle compliant!
### 2. Unittests
### 3. BaseModel
### 4. Create BaseModel from dictionary
### 5. Store first object
### 6. Console 0.0.1
### 7. Console 0.1
### 8. First User
### 9. More classes!
### 10. Console 1.0

## Advanced Tasks
### 11. All instances by class name
### 12. Count instances
### 13. Show
### 14. Destroy
### 15. Update
### 16. Update from dictionary
### 17. Unittests for the Console!

---

## Authors Page
* AUTHORS file is at the root of the repository, listing all individuals having contributed content to the repository.
* For how it is generated, see 'generate-authors.sh'.

---
