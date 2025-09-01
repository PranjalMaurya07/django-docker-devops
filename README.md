
# Django Notes App – DevOps Extension

This project is a containerized Django Notes App with a MySQL database and Nginx reverse proxy.
Originally a Django app, I extended it by integrating DevOps practices for seamless development and deployment.
## My Contribution

- Dockerized the entire application (Django, MySQL, Nginx) using multi-container setup with docker-compose.
- Added Nginx reverse proxy for handling client requests and serving static content.
- Integrated MySQL as the relational database with persistent volumes.
- Implemented health checks for Django and MySQL services.
- Secured configuration using environment variables from .env file.
- Automated Django migrations during container startup.

# Tech Stack
- Backend: Django (Python)  
- Database: MySQL
- Reverse Proxy: Nginx
- Containerization: Docker & Docker Compose
   
## Setup & Run

1. Clone the repo:
   ```bash
   git clone https://github.com/PranjalMaurya07/django-docker-devops.git
   cd django-notes-devops

2. Create an .env file in the root directory:

    ```bash
    MYSQL_ROOT_PASSWORD=root
    MYSQL_DATABASE=test_db

3. Build & run the containers:

    ```bash
    docker compose up --build -d

# Contacts

- Name : Pranjal Kumar Maurya
- Email : pranjalmaurya003@gmail.com
- Github : https://github.com/PranjalMaurya07
- LinkedIn : https://www.linkedin.com/in/pranjalmaurya07/
