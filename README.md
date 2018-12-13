[![Build Status](https://travis-ci.org/lcskrishna/python-sample-project.svg?branch=master)](https://travis-ci.org/lcskrishna/python-sample-project)

# python-sample-project
This is a toy example on how to implement a python project package.

## Extending this project
To extend this project use the following structure and modify file names and module names respectively in setup.py

## Installing the project

To install this as a python package, use the following:

```
% python setup.py install 
```
setup.py extends a class of 'install' that can be modified further according to the project requirements.

## Uninstall the project

To uninstall the project, use the following:

```
% python setup.py clean
```
This command cleans the directories and uininstalls the package. Here, the setup.py extends a class of 'clean' where we can add some custom logic based on the project requirements.
