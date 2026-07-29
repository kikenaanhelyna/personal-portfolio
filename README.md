# Personal Portfolio Website

A responsive personal portfolio website developed with PHP, MySQL, HTML, CSS, JavaScript, and Docker. The application demonstrates full-stack web development skills, database integration, and containerized deployment.

## Features
Responsive user interface
PHP backend
MySQL database integration
Docker Compose environment
Dynamic content rendering
Clean and organized project structure

## Technologies
PHP 8.2
MySQL 8
HTML5
CSS3
JavaScript
Docker
Docker Compose
Apache

## What I Learned

During this project I gained practical experience with:

Building a PHP web application
Connecting PHP to a MySQL database
Working with Docker containers
Creating and importing SQL databases
Organizing a full-stack project
Using Git and GitHub for version control

## Getting Started

### 1. Clone the repository
git clone https://github.com/Anhelyna/personal-portfolio.git
cd personal-portfolio

#### 1.1 This project uses a MySQL database.
Host: db
User: root
Password: root
Database name: mydb

##### 1.1.1 Import the tables
docker exec -i your_db_container_name mysql -u root -proot mydb < database.sql

### 2. Start containers
`bash
docker-compose up --build

### 3. Open in browser
http://localhost:8080


## Docker services
### Web Server (PHP + Apache)
Runs on port: 8080

### Database (MySQL)
Runs on port: 3306

