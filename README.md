# FlaskCRUDy

FlaskCRUDy is a simple CRUD (Create, Read, Update, Delete) web application built with Flask, the lightweight WSGI web application framework in Python. This project demonstrates basic CRUD operations on a simple data model.

## Features
1. User Authentication: Users can register for an account and log in to the application.
2. Create Blog Posts: Logged-in users can create new blog posts and upload images.
3. Read Blog Posts: Users can view all blog posts or filter to see only posts from specific users.
4. Update Blog Posts: Users can edit their own blog posts.
5. Delete Blog Posts: Users can delete their own blog posts.
6. Database Integration: The application connects to a local database to store user and blog post information.
7. Logout: Users can securely log out of the application.
  

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

- Python 3.6 or higher
- Flask
- A virtual environment (optional but recommended)

### Installation

1. Clone the repository:
   ```
   git clone https://github.com/yourusername/FlaskCRUDy.git
   ```
2. Navigate to the project directory:
   ```
   cd FlaskCRUDy
   ```
3. (Optional) Set up a virtual environment:
   ```
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```
4. Install the requirements:
   ```
   pip install -r requirements.txt
   ```

### Running the Application

1. Set the FLASK_APP environment variable:
   ```
   export FLASK_APP=app.py  # On Windows use `set FLASK_APP=app.py`
   ```
2. Run the Flask application:
   ```
   flask run
   ```
3. Open your web browser and navigate to `http://127.0.0.1:5000/` to see the application in action.

## Built With

- [Flask](http://flask.pocoo.org/) - The web framework used
