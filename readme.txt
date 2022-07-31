In our pc we install the python's different versions to work with different projects. Sometimes if we use python 's any different version with the existing project it may not work properly because sometimes any package does not work with python any package so to work efficiently we need to manage the version of pyhton as well as the third party packages.
So to manage the version we have virtual environment in python.
When we create virtual environment and install any package or module in this environment it will not be available outside of this environment.
And the package that we installed in the python main (without any environment will also not available in this)
we can say that virtual environment creates a new python for that perticular work.

so commands for the python virtaul environments are as follow

any path>pip install virtualenv   | and press enter it will install the virtualenv packages in the computer

now open the folder where we want to create the virtual environment ->

path>virtualenv folder_name   | folder_name is the new folder that we are creating in this folder all the dependencies will be installed on pressing enter.

not to activate the virtualenv use command 

path\folder_name>Scripts\actiate

to deactivate the virtualenv use

(folder_name)path\folder_name>deactivate     | here folder_name at the starting is showing that we are in the virtual environment , we acn come out this folder_name and make our own folder to create the project.


if we need to give this project to anybody we will not give the folder_name folder because it is very big in size

to give anybody we will give the source code along with requirements.txt file 

How to generate the requirements.txt file ??

path>pip freeze > requirements.txt

------

to install any specific pversion of package we can use the command ->

pip install package_name==x.x.xx  | version

so when we will give the requirements.txt file to anybody he can install the dependencies by the given above command.



