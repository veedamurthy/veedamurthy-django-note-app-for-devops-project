This is a simple notes app built with React and Django.
Requirements

    Python 3.9
    install docker
   
Installation

    Clone the repository

git clone https://github.com/veedamurthy/veedamurthy-django-note-app-for-devops-project.git

    Build the app

docker build -t notes-app .

    Run the app

docker run -d -p 8000:8000 notes-app:latest

