# Python Virtual Enviroments

If you don't know why virtual enviorments are important to use.  
Please follow this link http://docs.python-guide.org/en/latest/dev/virtualenvs/  



Install virtualenv via pip:  (pip) Python package management system  
`$ pip install virtualenv`  
`$ pip install virtualenvwrapper`  

In order to use virtualenvwrapper you should add two lines to your shell startup file (e.g., .bashrc):  
`export WORKON_HOME=$HOME/.virtualenvs`  
`source /usr/local/bin/virtualenvwrapper.sh`  

 Following are the commands you will use most often:  

* `mkvirtualenv` -  used to create a new virtual environment. When you create a new environment it automatically becomes the active environment.  
  * To specify the version of python that the virtual enviroment should run: Execute this command (e.g., Python3)  
  * `$ mkvirtualenv --python=/usr/bin/python3 my_virtualenv`
* `rmvirtualenv` -  used to remove an existing virtual environment. The environment must be deactivated (see below) before it can be removed.
* `workon` -  used to activate a virtual environment. Will also list all existing virtual environments if no argument is passed.
* `deactivate` -  used to deactivate the currently active virtual environment. Note that workon will automatically deactivate the current environment before activating a new one.


