# Flask Task Manager 
A lightweight and modular Flask-based task management web application designed for productivity, user authentication, and real-time task tracking. Built with scalability, clean architecture, and developer experience in mind.

# Overview of the Project
Through a dynamic and user-friendly user interface, FlaskTaskManager is a CRUD-based task manager that enables users to register, log in, create tasks, mark them as complete, and delete them. The following full-stack web development concepts are illustrated in this project:

- RESTful routing
- Modular design blueprints for flasks
- Jinja2 templating
- For database abstraction, SQLAlchemy ORM
- Management of sessions
- For a responsive frontend, use Bootstrap
- Feedback and validation of the form

# The Reason I Built This
In order to incorporate important backend engineering principles, I created FlaskTaskManager as part of my efforts to better understand Flask and comprehend the architecture of real-world online applications. 

I gained from this project:
Learn and implement clear routing and concern separation
Discover how to handle persistent sessions and authenticate
Develop the ability to modularize big Flask apps
Rapidly prototype web applications that are focused on tasks

# Technologies Used
| Technology      | Description                                 |
| --------------- | ------------------------------------------- |
| **Flask**       | Core web framework (routing, server, logic) |
| **SQLite**      | Lightweight relational database             |
| **SQLAlchemy**  | ORM for abstracting raw SQL                 |
| **Jinja2**      | Templating engine                           |
| **Bootstrap 5** | UI styling and layout                       |
| **Werkzeug**    | Secure password hashing                     |
| **WTForms**     | Form handling and validation (optional)     |

# Installation & Setup
Requirements
- Python 3.7+
- Virtualenv (recommended)

Steps

```bash 

# Clone the repository
git clone https://github.com/ii310/FlaskTaskManager.git
cd FlaskTaskManager

# Create virtual environment & activate
python3 -m venv venv
source venv/bin/activate   # on Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Run the app
python run.py

```


App will run locally on: http://127.0.0.1:5000/
