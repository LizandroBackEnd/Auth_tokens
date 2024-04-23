<div align="center">   
<h1> Proyect Auth Tokens </h1> 
📅 Creation Date: 22/04/24  
</div> 
 
## Index


- [Description](#🎯-description)  
- [Deployment tools](#🔧​deployment-tools) 
- [Deployment](#💽-deployment) 
- [Project Organization](#📁-project-organization)
- [Technologies](#✨-technologies)


  

# 🎯 Description

The Auth Tokens project aims to create a small and basic application where we practice Auth security with Django, as well as the use of tokens to make requests to the application.

# 🔧​ Deployment tools  
 
To be able to use proyect Auth Tokens locally, you must have the following tools and languages installed: <br> 
- Python in its version 3, as the project is built on the most current version at the time of its creation. Downloading Python on operating systems like Windows or MacOS is simpler because it can be done through the interface, but on Linux, it would be done as follows:
  
Open a terminal and execute the following commands: <br>
<h3> Ubuntu/Debian </h3> 

```bash
sudo apt update
sudo apt install python3
```

<h3> Fedora </h3> 

```bash
sudo dnf install python3
```

<h3> Arch Linux </h3> 

```bash
sudo pacman -S python
```

Then, check if Python has been downloaded and installed correctly with the following command:

```bash
python3 --version
```

- `pip` is the Python package manager. It is a tool that allows you to install and manage additional software packages that are not distributed as part of Python's standard library, which is necessary to install the other tools. To download `pip` on Linux, it would be done as follows:

<h3> Ubuntu/Debian </h3> 

```bash
sudo apt update
sudo apt install python3-pip
```

<h3> Fedora </h3> 

```bash
sudo dnf install python3-pip
```

<h3> Arch Linux </h3> 

```bash
sudo pacman -S python-pip
```

Then check if it has been downloaded and installed correctly
```bash
pip3 --version
```

- Most of the time in Python 3, the module for creating virtual environments, venv, comes included with the standard Python installation, so you don't need to download anything additional to create a virtual environment. But if for some reason it is not installed, then you can download it using the following command:

Note: To run this command, you must be inside the Temachapi folder
```bash
pip install virtualenv
```

After that, you can create the virtual environment with the following command:
```bash
python3 -m venv env
```

# 💽 Deployment

To deploy the proyect Auth Tokens, you need to follow these steps: 

- Starting the virtual environment varies across different operating systems, which is done as follows:

<h3> Windows </h3> 

```bash
env\Scripts\activate
```

<h3> MacOS </h3> 

```bash
source env/bin/activate
```

<h3> Linux </h3> 

```bash
source env/bin/activate
```

- Before starting the server, you need to install all the modules, frameworks, and tools used in the project. We can install everything using the command:
```bash
pip install -r requirements.txt
```

- To start the server, the same command works for all operating systems:

```bash
python manage.py runserver
```
Once the server is started, it will provide you with a link. By accessing this link, you will be able to use Temachapi.

# 📁​ Project organization  

The project organization is very easy to understand, where: 

- In the `server` folder, we have the project configurations, application installations, modules, and tools necessary for the project. Additionally, this folder is where configuration needs to be done in order to deploy it when uploading to a web hosting service.
   
# ✨ Technologies
This project made use of the following technologies: 
  

| Technology         | Logo                                                                                                                             |
|--------------------|----------------------------------------------------------------------------------------------------------------------------------|
| Django             | <img src="https://www.vectorlogo.zone/logos/djangoproject/djangoproject-icon.svg" width="35">                                                                                                         |
| Django REST Framework | <img src="https://upload.vectorlogo.zone/logos/djangoproject/images/3a96fc19-0d1b-43de-86d6-5e506122ea1d.svg" width="100">                                                                                   |
| Python             | <img src="https://www.vectorlogo.zone/logos/python/python-icon.svg" width="35">                                                                                                         |

 

  