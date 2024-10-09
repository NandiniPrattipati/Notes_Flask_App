# Notes_Flask_App
This is a simple Notes app built with Python, Flask, SQLAlchemy, and Flask-Login. Users can sign up, log in, and create, view, and delete notes. The app demonstrates authentication, session management, and basic CRUD operations with a SQLite database.

**Features**
- User registration and login using Flask-Login.
- Secure password hashing and session management.
- Create, read, and delete notes for each authenticated user.
- User specific notes -- only logged in users can manage their own notes.
- Simple and mininal user interface (since I created this app to gain experience in backend development)

**Technologies Used**
- **Flask:** Web framework for building the app.
- **SQLAlchemy:** ORM for interacting with the database.
- **Flask-Login:** Provides user session management and authentication.
- **SQLite:** Database to store users and notes.
- **HTML/CSS:** Basic front-end layout.
- **Bootstrap:** For styling the UI components.

**Installation and Setup**
**Prerequisites:**
- **Python 3.x**
- **Virtual Environment(optional but recommended)**

**Usage**
- **Signup** for a new accoutn on the "Sign Up" page.
- **Login** with your credentials.
- Create a new notes on the home page.
- View or delete notes. 

**Project Structure**
notes-app/
│
├── app.py              # Main Flask app
├── models.py           # SQLAlchemy models (User and Note)
├── forms.py            # Flask-WTF forms
├── templates/          # HTML templates
│   ├── base.html       # Base template
│   ├── home.html       # Notes list page
│   ├── login.html      # Login page
│   └── signup.html     # Signup page
├── static/             # Static files (CSS, JS, images)
│   └── main.css        # Custom styles
├── requirements.txt    # List of dependencies
├── README.md           # Project documentation
└── .gitignore          # Ignore unnecessary files in Git

**Future Improvements**
- **Edit Notes:** Add functionality to update existing notes.
- **Pagination:** Implement pagination for a large number of notes.
- **Search:** Add a search feature to find notes by content.
- **REST API:** Expose the functionality via a REST API for external clients.
