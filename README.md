Welcome to the Social Media Platform project built using Django! This project aims to create a basic social media platform where users can register, log in, post updates, connect with friends, and more. The platform provides a foundation that you can extend and customize to create your own unique social media experience.
Features :-
User registration and authentication
User profiles with profile pictures and bio
News feed displaying posts from friends
Post creation and deletion
Like on posts
Follow to a user & see its post on home feed
unfollow to a user
User search functionality
Responsive and user-friendly design
User Follower list
Personal User Chat
Post Sharing


ensure you have the following installed:

Python (version 3.6 or higher)
Django (version 3.2 or higher)
Git

Installation
Clone the repository:

git clone https://github.com/anurag611/memeshareapp_project.git

Navigate to the project directory:
cd memeshareapp

Create a virtual environment (recommended):
virtualenv venv  or python3 -m venv venv

Activate the virtual environment:


On Windows:
venv\Scripts\activate
On macOS and Linux:

source venv/bin/activate
Install the project dependencies:

pip install requirement.txt  (Make sure you are in main directory where .txt file is present)
Perform database migrations:

run
python manage.py migrate   OR  python3 manage.py migrate


Run the development server:
python manage.py runserver OR python3 manage.py runserveR
Access the application in your web browser at http://127.0.0.1:8000/.
