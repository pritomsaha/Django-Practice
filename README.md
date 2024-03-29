# Django

## Setting up Django 

### Step-1: Install and upgrade pip3 (pip for python3)

Install pip3 using following command:

	sudo apt-get install python3-pip
	
check pip3 version by following command:

	pip3 -V 

if pip3 is not latest version upgrade by following command:

	pip3 install --upgrade pip 

### Step-2: Install virtualenv
	
	pip3 install virtualenv or sudo apt-get install python3-virtualenv

### Step-3: Create virtual environment

Go to your project directory
	cd [your project directory]

create virtual env using following command:

	virtualenv -p python3 [where to create env]

### Step-4: Activate virtual environment

every time when you start developing you need to activate virtual environment 
	source [env directory]/bin/activate

### Step-5: Install Django

	pip install Django

Or If you use mysql as your database use the following command:

	pip install Django mysqlclient

Check your Django version using following command:  
	
	python -m django --version

### Step-6: Start Project

	django-admin startproject [project-name]

### Step-7: Run server

	python manage.py runserver

It will run the server in localhost in port number: 8000
check if server is running in your browser using
	localhost:8000
 
You can change your Ip/PortNumber using following command
	
	python manage.py runserver ip:port
