# POO and Algorithms with Python

Optimization Algorithms
- Solve problems in a rational way
- Maximize or minimize with a function
- Usually there are constrains

## Virtual environments

I have been using [pyenv](https://github.com/pyenv/pyenv) to manage python versions on my Mac, and i just found it has another library called [pyenv-virtualenv](https://github.com/pyenv/pyenv-virtualenv), which allows me to create a virtual environment based on a python version.

In pyenv i have 1 python version installed (Python 3.9.1) and inside that python version, i have a virtual environment made for this repository called "platzi-python". This environment has several libraries installed, and those can be found in a file in the root folder called "requirements.txt". It was created via terminal, cd proyect-folder and typing the command "pip freeze > requirements.txt". libraries can be uninstalled using the command "pip uninstall -r requirements.txt -y" (-y is kind of "yes to all"), and can be reinstalled using the command "pip install -r requirements.txt"

To create a virtual environment within a python version i used [this link](https://akrabat.com/creating-virtual-environments-with-pyenv/) as reference. It basically says that using the command "pyenv virtualenv 2.7.16 venv_name", we can create a venv within the specified python verison.