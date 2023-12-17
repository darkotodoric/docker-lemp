# Dockerized LEMP Stack
This repository contains a Dockerized LEMP (Linux, Nginx, MySQL, PHP) stack, designed to streamline your web development environment setup. With Docker, you can easily deploy and configure this LEMP stack on any server with minimal effort.

## Features
- **Nginx**: A high-performance web server to serve your web applications.
- **MySQL**: A powerful relational database management system for storing your data.
- **PHP**: A scripting language for dynamic web application development.
- **Docker**: Containerization for portability and easy deployment.

## Prerequisites
Before you begin, ensure you have the following installed:

- Docker: [Installation Guide](https://docs.docker.com/get-docker/)
- Docker Compose: [Installation Guide](https://docs.docker.com/compose/install/)

## Usage
1. Clone this repository to your local machine:

   ```bash
   git clone git@github.com:darkotodoric/docker-lemp.git

2. Navigate to the project directory:

    ```bash
    cd docker-lemp

3. Start the Docker containers

    ```bash
    docker-compose up -d

4. Access your web application at http://localhost. You can also configure your server to serve this stack on a specific domain.

## Configuration
You can customize the LEMP stack configuration by editing the respective configuration files:
 - Nginx configuration: `./nginx/nginx.conf`
 - MySQL configuration: `./mysql/my.cnf`
 - PHP configuration: `./php/php.ini`

## Contributing
Contributions are welcome! Feel free to open issues or submit pull requests to improve this project.

