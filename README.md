# Forum_app
This is a simple forum application built using Flask, HTML, CSS, and JavaScript. It allows users to register, log in, and interact with the platform. Users can also update their profiles and like posts, with each user restricted to liking a post only once.

# Features
- User Registration
- User Login
- Dashboard
- Like Feature
- Profile Update
- Responsive Design

# Usage
- Registration
  - Navigate to the registration page by clicking "Register" on the home page.
  - Fill out the registration form and submit to create a new account.
- Login
  - Navigate to the login page by clicking "Login" on the home page.
  - Fill out the login form and submit to log in to your account.
- Creating Posts
  - After logging in, navigate to the dashboard.
  - Fill out the post form and submit to create a new post.
- Liking Posts
  - On the dashboard, click the "Like" button next to a post to like it.
- Deleting Posts
  - On the dashboard, click the "Delete" button next to a post to delete it.
- Updating Profile
  - You can add a form or link on the dashboard to navigate to a profile update page (not included in the basic setup but can be added).

# Installation and Setup
1.**Clone the repository**:
bash
'''
git clone https://github.com/your-username/forum-application.git
cd forum-application
'''
2.**Create a virtual environment**:
bash
'''
python -m venv venv
source venv/bin/activate    # On Linux/Mac
venv\Scripts\activate       # On Windows
'''
3.**Install dependencies**:
bash
'''
pip install -r requirements.txt
'''
4.**Run the application**:
bash
'''
flask run
'''
5.**Access the application in your browser**:
bash
'''
Navigate to http://127.0.0.1:5000
'''

# Folder structure
forum-application/
├── static/
│   ├── style.css
│   ├── script.js
├── templates/
│   ├── base.html
│   ├── register.html
│   ├── login.html
│   ├── dashboard.html
├── app.py
├── requirements.txt
├── README.md
