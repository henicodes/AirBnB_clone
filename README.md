# 0x00. AirBnB clone - The console
This is the first step towards building your first full web application: the AirBnB clone. This first step is very important because you will use what you build during this project with all other following projects: HTML/CSS templating, database storage, API, front-end integration…
### Table of contents
- 01 - Introduction
- 02 - Environment
- 03 - Installation
- 04 - Execution
- 05 - Testing
- 06 - Usage
- 07 - Authors
### 01 - Introduction
This is the first step towards building your first full web application: the AirBnB clone. This first step is very important because you will use what you build during this project with all other following projects: HTML/CSS templating, database storage, API, front-end integration…
Each task is linked and will help you to:

- put in place a parent class (called BaseModel) to take care of the initialization, serialization and deserialization of your future instances
- create a simple flow of serialization/deserialization: Instance <-> Dictionary <-> JSON string <-> file
- create all classes used for AirBnB (User, State, City, Place…) that inherit from BaseModel
- create the first abstracted storage engine of the project: File storage.
- create all unittests to validate all our classes and storage engine
### 02 - Environment
All the development and testing was runned over an operating system Ubuntu 20.04 LTS using programming language Python 3.8.3. The editors used were VIM 8.1.2269, VSCode 1.6.1 and Atom 1.58.0 . Control version using Git 2.25.1.
### 03 - Installation
`git clone https://github.com/henicodes/AirBnB_clone.git`
- cd into the AirBnB_clone
- run `./console.py`
### 04 - Execution
![alt text](https://github.com/henicodes/AirBnB_clone/blob/master/AirBnB%20clone%20execution.JPG)
### 05 - Testing
All the test are defined in the tests folder.
### Python Unit Tests
- unittest module
- File extension .py
- Files and folders star with test_
- Organization:for models/base.py, unit tests in: tests/test_models/test_base.py
- Execution command: python3 -m unittest discover tests
- or: python3 -m unittest tests/test_models/test_base.py
### run test in interactive mode
`echo "python3 -m unittest discover tests" | bash`
### run test in non-interactive mode
`python3 -m unittest discover tests`
### 06 - Usage
### 07 - Authors
- Henok Assefa
- Yonas Addis
