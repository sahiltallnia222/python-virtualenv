In our pc we install the python's different versions to work with different projects. Sometimes if we use python 's any different version with the existing project it may not work properly because sometimes any package does not work with python any package so to work efficiently we need to manage the version of pyhton as well as the third party packages.
So to manage the version we have virtual environment in python.
When we create virtual environment and install any package or module in this environment it will not be available outside of this environment.
And the package that we installed in the python main (without any environment will also not available in this)
we can say that virtual environment creates a new python for that perticular work.

so commands for the python virtaul environments are as follow

------any path>pip install virtualenv---------   | and press enter it will install the virtualenv packages in the computer

now open the folder where we want to create the virtual environment ->

------------path>virtualenv folder_name----------   | folder_name is the new folder that we are creating in this folder all the dependencies will be installed on pressing enter.

not to activate the virtualenv use command 

---------path\folder_name>Scripts\actiate----------------

to deactivate the virtualenv use

----------------------(folder_name)path\folder_name>deactivate----------     | here folder_name at the starting is showing that we are in the virtual environment , we acn come out this folder_name and make our own folder to create the project.


if we need to give this project to anybody we will not give the folder_name folder because it is very big in size

to give anybody we will give the source code along with requirements.txt file 

How to generate the requirements.txt file ??

--------path>pip freeze > requirements.txt----------------

------

to install any specific pversion of package we can use the command ->

----------------pip install package_name==x.x.xx---------------------  | version

so when we will give the requirements.txt file to anybody he can install the dependencies by the given above command.

But if there are huge number of dependencies that it is very hard to install one by one so how can we do this ->

----------------path > pip install -r .\requirements.txt----------------

it will automatically install all the dependencies.

if we want to make a vritual environment that also have the packages of system pyhton (main)

use 
--------------path> pip install --system-site-package virutal_env_folder_name----------------------

to create the virtual env for the specific python version

use
----------path>virtualenv venv --python=python3.10   for 3.10 version same for other----------


to check all the python versions in pc use

-----py -0-------

or 

----py --list ------



Which python version will be default to do so 

The python folder with version persent at the first in the paths.

if you want to make any specific python version as the system default version of python then 

go to the environment path in system 

open path ->

move up all the paths related to that version.


environment> script.py\activate
deactivate

-----------------------------------------SAHIL TALLNIA ------------------------------->
