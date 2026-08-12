This repository contains the source code for the Django BloggApp. This is a real-world, feature-rich blogging system — from models, templates and forms to permissions, dashboards and deployment

Features implemented
Multi-role system (Admin / Manager / Editor / Author)
Create / Read / Update / Delete (CRUD) for posts & categories
Unique slug generation & prepopulation
Media (image) upload & configuration
Comment system (only authenticated users can comment)
Manager & Editor dashboards with counts and tables
Granular permission checks (using Django Groups & Permissions + custom checks)
Search feature with retained search term in textbox
Deployment on PythonAnywhere

Requirements
Python 3.10+ (recommended)
Django 4.x (see requirements.txt) - always use latest version
A virtual environment tool (venv / virtualenv)
PostgreSQL / MySQL or SQLite for development
