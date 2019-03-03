# Setting up a python IDE # 

## Preferred folder structure for python projects ##

Switch to custom installing and use the intended folder. If you just use eclipse wit PyDev for python  development, there is no need to take care about windows environmental variables. The IDE will take care about environmental variables like PATH, PYTHONPATH and PY_HOME.

```
JRE installed within windows standard pathes

C:\SwDev	(root folder)
		\python
				\Python37-64	(python example interpreter)
		\eclipse	(python IDE)
		\eclipse_workspace	(eclipse specific workspace)
		\git	(git specific workspace)
			\PythonProject	(python example project)
							\src
							\doc
							\img
```
	

## installation of eclipse ##
JRE and Eclipse have to fit to gather (e.g. 64 bit and version), python environment can be of any version.

## download and install jre ##
Eclipse is developed with Java therefore the latest JRE (Java Runtime Environment) is needed.

![JRE_WINDOWS_64bit](https://www.oracle.com/technetwork/java/javase/downloads/jre8-downloads-2133155.html "jre-*-windows-x64.exe")

## download and install eclipse ## 
![ECLIPSE_DOWNLOAD_LINK](https://www.eclipse.org/downloads/download.php?file=/oomph/epp/2018-12/R/eclipse-inst-win64.exe "Eclipse Windows 64bit 2018")

## download and install python ##
Select the required version, currently I prefer the latest 64bit version. But this depends on packages you want/have to use.

![PYTHON_DOWNLOAD_LINK](https://www.python.org/ftp/python/3.7.2/python-3.7.2-amd64.exe "Python 3.7 64bit")

## download and install eclipse python packages ##
1. go to Menu "Help>Eclipse Market Place" and search for PyDev
1. restart eclipse
1. go to Menu "Help>Eclipse Market Place" and search for CodeMix

## engage pydev with python
1. go to menu "Window>Preferences"
1. go to sub menu "PyDev>Interpreters>Python Interpreter"
1. add python.exe of required interpreter (see screenshot below)

![Install_PyDev](../images/eclipse_engage_pydev_with_python.png "engage pydev with python")






