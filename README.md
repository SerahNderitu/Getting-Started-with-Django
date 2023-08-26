# Getting-Started-with-Django
# Learn how to effectively install Django

Django is a well-liked option for developing sophisticated and feature-rich online applications because of its wide ecosystem of reusable parts and packages, emphasis on security, and scalability.

As a high-level Python web framework, Django gives developers the ability to swiftly and efficiently build robust and scalable online applications.

## Installing Django

To install Django, you need to have Python installed, and a package manager like PIP.

## Python Installation
Run this command in your terminal to see if Python is installed on your computer.
```Python
python --version
```

If you have Python already installed, your output will show your installed Python version number on your command prompt. Here, I have Python 3.10.10 installed. Your output can have the same or a different version depending on what you installed;
```
Python 3.10.10
```

If you find that you do not have Python installed on your computer, then you have to install Python first.

Next, check if you have a package manager PIP installed. On your command prompt, enter the following;
```
pip --version
```

If you have pip already installed, you will get an output with the version number.
```
Output
pip 22.0.4 from c:\python310\lib\site-packages\pip (python 3.10.10)
```

The Pip version may vary. In this case, we have Pip version 22.0.4 already installed.


## Creating Django’s Virtual Environment

A virtual environment is a crucial tool for managing and isolating dependencies in a Django project. 

It allows developers to build a distinct environment with its own set of installed packages and Python interpreters, ensuring that the project's dependencies are consistent and do not conflict with other projects.

Now you can navigate to a location where you want to create your Django project and create a virtual environment. Your virtual environment should have a name of your choice. In this case, we’re going to call it **mysite**. 

#### On Unix/MacOS:

```
python3 -m venv mysite
```

Then, activate your virtual environment
```
source mysite/bin/activate
```

#### On Windows:
```
py -m venv mysite
```

Then, activate your virtual environment
```
mysite\Scripts\activate.bat
```

If the activation is successful your virtual environment's name, in this case (mysite), will appear at the start of the command prompt.

Point to Note: To effectively work on your Django project, you must activate the virtual environment each time you access the command prompt.


Now that we have a virtual environment installed and activated, we can go ahead and install Django. We shall use the Pip package manager to do this.
```
pip install Django
```

This will update Django to the most recent version and install it in your system. Wait for a moment as the installation is in the process.

You can specify a specific Django version you want to install as follows;
```
pip install Django==<version>
```


## Check your Django Installation

Run the following command to check if Django was installed successfully and the version that was installed.
```
django-admin --version
```

The output should have the installed Django version

**All done!** Now that Django is installed and operating in a virtual environment, your new project is ready to go!



