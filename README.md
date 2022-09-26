# Author: Paulo Igor Rivero




# You can create a virtual enviroment an run the "pip install -r requirements.txt" then everything you need will be installed.
## You can first create a virtual enviroment before clone this repo.
## As a advice I'm dropping a link explain how to create a venv folder to install all the dependences
### https://docs.python.org/3/library/venv.html
### https://packaging.python.org/en/latest/guides/installing-using-pip-and-virtual-environments/
### After you reach the folder you want to create a virtual enviroment project, you can use the following steps:
### The main commands are: "python3 -m venv env" where env is you virtual enviroment folder name
### Then enter the folder you created : "cd env"
### Then activate the virtual env: "source bin/activate "
### Now you can git clone this project: "git clone https://github.com/IgorRivero/hubs-project.git"

# Important!
### To make sure the project will run, only check in the beggin path of the sql file is setted. A dynamic path was created, but is important to make sure, this way everithing will run.
### sql file is located in: etc/jupyter/nbconfig/notebook.d/hubs_files/hubs_events.sql
### the script is a notebook file located in : etc/jupyter/nbconfig/notebook.d/hubs_files/hubs_events.ipynb


## To run this project first you have to make sure to have installed:
## Python at least version 3.9.6
    You can find on this link https://www.python.org/downloads/release/python-396/
## Pyspark at least version 3.1.3
    You can find on this link https://spark.apache.org/news/3-1-3-released.html
    and
    https://sparkbyexamples.com/pyspark/install-pyspark-in-jupyter-on-mac-using-homebrew/
## Java version 8
    You can find on this link https://www.java.com/pt-BR/download/ie_manual.jsp?locale=pt_BR
## Jupyter.
    You can find on this link https://jupyter.org/install

### NOTES: This project was developed in a Databricks notebook. Then I migrate it to a jupyter notebook. It works both in a isolated enviroment, 
### runned in a docker image using jupyter notebook and also ran it in a virtual enviroment created with python 3.9.+ , pyspark 3.1.+ , Java 8 and Jupyter. 
### Using Visual Studio Code. 


