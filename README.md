# Hello DevOps App

This is my first Flask project.

## Tech Used
- Python
- Flask
- Git
- GitHub

## How to Run

pip install -r requirements.txt
python app.py

## End result(output)

Hello cloud engineer


# Flask DevOps App (Dockerized)

## Project Description

This project demonstrates how to containerize a simple Flask web application using Docker.
The goal of this project is to understand the basic DevOps workflow including application development, dependency management, containerization, and version control.

The application runs a simple Flask server that returns a message when accessed from a web browser.

---

## Technologies Used

* Python
* Flask
* Docker
* Git
* GitHub

---

## Project Structure

hello-devops-app

app.py
requirements.txt
Dockerfile
README.md
.gitignore

---

## Run the Application Locally

Step 1: Install dependencies

pip install -r requirements.txt

Step 2: Run the Flask application

python app.py

Step 3: Open browser

http://localhost:5000

---

## Run the Application Using Docker

Step 1: Build the Docker image

docker build -t flask-devops-app .

Step 2: Run the container

docker run -p 5000:5000 flask-devops-app

Step 3: Open browser

http://localhost:5000

---

## What I Learned From This Project

* Creating a basic Flask web application
* Managing dependencies using requirements.txt
* Writing a Dockerfile
* Building Docker images
* Running containers
* Using Git and GitHub for version control

---

## Future Improvements

* Add CI/CD pipeline
* Deploy the application to cloud platforms like AWS or GCP
* Add database integration
