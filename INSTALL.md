# Install data science environment

## Install Python

To get started working with Python 3, you’ll need to have access to the Python interpreter. There are several common ways to accomplish this:

Python can be obtained from the Python Software Foundation website at python.org. Typically, that involves downloading the appropriate installer for your operating system and running it on your machine.
Some operating systems, notably Linux, provide a package manager that can be run to install Python.
On macOS, the best way to install Python 3 involves installing a package manager called Homebrew. You’ll see how to do this in the relevant section in the tutorial.
    
You can find the relevant information for your OS in this tutorial:

https://realpython.com/installing-python/

## Install Pipenv

Pipenv is a Python dependency manager. Functionally, it’s a combination of pip and virtualenv. It’s officially recommended by Python.org. It’s used it to install and keep track of required project dependencies and keep them isolated from the rest of the system.

    pip install pipenv


## Clone this repository

Use git to make a working copy of this repository


    git clone https://github.com/alabarga/python-data-science-personalized-medicine-2019.git

or download and unzip

https://github.com/alabarga/python-data-science-personalized-medicine-2019/archive/master.zip


    cd python-data-science-personalized-medicine-2019

## Install data science libraries

    pipenv install pandas numpy scikit-learn matplotlib seaborn sdv lime shap
    

You’ll also notice a couple of files called Pipfile and Pipfile.lock have been created – this is a record of the whole dependency graph of the project. It should be checked into source control, as Pipenv can use it to ensure deterministic builds.

## Install Jupyter

    pipenv install jupyter
    
    pipenv run jupyter notebook






