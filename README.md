# API Final Project Documentation

# Description


The API endpoints for this project provide the functionality to create, edit and delete users, roles for each user, such as Customer, Delivery Crew or Manager, menu items, categories for menu items,  shopping cart, and orders. Every API endpoint has authorization and permissions constraints as well as throttling, pagination, and filtering.

## Project Structure

This project consists mainly of two apps, *littlelemon* and *api*.

**littlelemon app**

This app contains the models' definition to create the entity relationships required by the *api* app.

**api app**

This app contains the URLs dispatchers (routers), serializers, and views for every endpoint of the API. Additionally, it contains helpers classes that are inherited by class-based views.

**config dir**

This directory contains the configuration files of the project, such as the `settings.py` file and the `urls.py` file which contains the main URL dispatchers of the project.

## Installation

**Clone the repository**

```bash
git clone https://github.com/Rohitisavailable/Little-Lemon.git 
```

**Create the virtual environment and install the dependencies**

```bash
pipenv install
```
**Run the server using**

```bash
python manage.py runserver
```
