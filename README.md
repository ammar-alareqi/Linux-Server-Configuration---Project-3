# Project 3: Linux Server Configuration

## Overview
A baseline installation of a Linux server is prepared to host a web applications. It will be secured from a number of attack vectors, install and configure a database server, and deploy of **Item Catalog** web applications onto it.

## Server Info

- **Server Provider**: AWS Lightsail
- **IP address:** 3.8.111.184
- **Port**: 2200
- **Installed software**: Flask, SQLAlchemey, OAUTH, PostgreSQL, Apache2, mod-wsgi, Git
- **Third party resources**: Amazon (AWS Lightsil)

## Configuration

- Create user **grader** and generate a SSH key for him.
- Congigure the firewall and set the needed ports.
- Install Apache2 server and mod-wsgi.
- Install PostgreSQL and create a new user **"catalog"**.
- Install Flask and SQLAlchemey.
- Install Git and clone the **Item Catalog** project.
- Run the db_setup.py and seeder.py to generate data for the database.
- Configure the apache server to run wsgi app.

