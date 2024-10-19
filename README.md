# Django_OpenAI_Chatbot

Django Chatbot
A simple chatbot web application built using Django and integrated with OpenAI GPT-3.5 to generate intelligent responses. The app allows users to interact with the chatbot after logging in, with each chat stored in a database for future reference.

Features
User registration, login, and logout functionality.
Secure interaction with the chatbot using OpenAI’s GPT-3.5 API.
Stores chat history for logged-in users.
Simple and intuitive web-based interface.

Technologies Used
Python 3.12
Django 5.1.1
OpenAI API for chatbot responses
SQLite (default Django database)
HTML/CSS for the frontend

1. Setup Instructions
Prerequisites
Python 3.x installed on your system.
An OpenAI API key. You can generate one from the OpenAI Dashboard.
Git installed for cloning the project.

2. Clone the Repository
git clone https://github.com/Ranishree77/Django-OpenAI-Chatbot.git
cd Django-OpenAI-Chatbot

3. Create a Virtual Environment
python -m venv myenv
myenv\Scripts\activate     # On Windows

4. Run the development Server
python manage.py runserver
Now, open http://127.0.0.1:8000 in your browser.

Usage
Register a new user or log in using existing credentials.
Interact with the chatbot by typing a message and submitting it.
View your chat history on the same page.
Logout when done.

Contributing
Feel free to open issues or submit pull requests for improvements.






