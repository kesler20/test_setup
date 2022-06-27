# Project Setup
in order to install things in python as a user administrator add --user at the end of the install statemnet 
for instance
 - `pip install -r requirements.txt --user`
 - `pip install flask --user`
 - `python -m pip install --user --upgrade pip`

just a base template repo which can be used to start python projects

1. create new repository ``mkdir directory``
2. cd into the repository and create a virtualenvironment ``conda create -n myenv sqlite``
3. activate the new virtualenv ``conda activate myenv``
4. install dependencies ``conda install pandas``
5. make the dependencies explicit `pip freeze > requriements.txt``

To move files into the root folder after cloning this repository

``xcopy * ../``

then click D o the question they ask.

## For a Linux computer

To pip install packages on linux 
``python3 -m pip install pandas``

To install pip 
``sudo apt install python3-pip``

to delete files
``rm filename``  

Remove directories (empty)
``rmdir directory``

Remove non-empty directory
``rm -rf directory``

for more information check [here](https://github.com/kesler20/Config_settings/blob/master/Linux/Linux.md)
