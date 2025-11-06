# 🛠️Basic Task Manager(Flask CRUD Application)
## Overview
Simple to-do-list built using the Flask web framework with the purpose to demonstrate the basic full-stack web development fundamentals, specifically the implementation of  CRUD interface.
### Features
The Task Manager provides the basics needed for managing a list;
**Create (C):** Add new tasks
**Read   (R):** Display existing task
**Update (U):** Edit existing task
**Delete (D):** Remove task
## Tech Stack
**- BackEnd Framework:** Python 3.10+
**- Web Framework:** Flask
**- ORM (Database Interface):** Flask-SQLAlchemy
**- Markup:** HTML/CSS
## Installation Setup
### Prerequisites
Python 3
### 1. Clone the Repository
```
git clone [YOUR_REPOSITORY_URL]
cd task-manager-flask
```
### 2. Set up the Virtual Environment (Recommended)
Using a virtual environment prevents dependency conflicts with other Python projects.
```
# Create the environment
python3 -m venv venv
# Activate the environment (macOS/Linux)
source venv/bin/activate
# Activate the environment (Windows)
venv\Scripts\activate
```
### 3. Install Dependencies
The necessary dependencies for this project are managed in the requirements.txt file. Install them using pip:
```
pip install -r requirements.txt
```

### 4. Run the Application
The application is run directly via the main Python file. The database (task.db) will be automatically created on the first run.
```
python app.py
```
