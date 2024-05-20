# WP-Docker-boilerplate
This repository contains a Docker Compose setup to run a WordPress development environment with MySQL and phpMyAdmin.

The setup is designed to streamline the process of getting a local WordPress instance up and running quickly with the following services:

1. MySQL 5.7: A MySQL database server.
2. WordPress (latest version): The WordPress CMS.
3. phpMyAdmin: A web interface for MySQL database management.

## Repository Structure
WORDPRESS-DOCKER/
├── .git/
├── .srv/
│   ├── database/          # MySQL database files
│   ├── wordpress/         # WordPress files
│   └── custom.ini         # Custom PHP configuration
├── plugin/
│   └── my-core.php        # Custom plugin file
├── theme/
│   └── my-theme/          # Custom theme directory
├── .gitignore
└── docker-compose.yml     # Docker Compose configuration file

## Getting Started
Clone the repository:

### Copy code
```
git clone https://github.com/your-username/wordpress-docker-boilerplate.git
cd wordpress-docker-boilerplate
```

### Start the services:
```
docker-compose up -d
```

### Access the services:
WordPress: http://localhost:8000
phpMyAdmin: http://localhost:8181
