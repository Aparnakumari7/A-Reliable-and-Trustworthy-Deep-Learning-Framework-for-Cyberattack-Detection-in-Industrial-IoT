# Trustworthy and Reliable Deep Learning-Based Cyberattack Detection

A Django-based web application for detecting cyberattacks in Industrial IoT environments using deep learning techniques.

## Features

- Deep learning-based cyberattack detection
- User authentication system
- Real-time attack prediction
- Interactive data visualization
- Download predicted datasets
- View attack type ratios and statistics
- Remote user and service provider interfaces

## Prerequisites

- [Docker Desktop](https://www.docker.com/products/docker-desktop/)

## Quick Start

1. Clone or download this repository
2. Open terminal in the project directory
3. Run the application using Docker:
```bash
docker compose up
```
4. Access the application at: http://localhost:8000

## Project Structure

```
trustworthy_and_reliable_deep_learning/
├── Remote_User/            # Remote user interface
├── Service_Provider/       # Service provider interface
├── Template/              # HTML templates and static files
│   ├── htmls/            # HTML templates
│   ├── images/           # Static images
│   └── media/           # User uploaded media
├── Dockerfile            # Docker configuration
├── docker-compose.yml    # Docker services configuration
└── requirements.txt      # Python dependencies
```

## Technology Stack

- Python 3.9
- Django 4.2+
- TensorFlow
- MySQL
- NumPy
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn

## Development

To modify the application:

1. Make changes to the code
2. Rebuild and restart containers:
```bash
docker compose up --build
```

## Stopping the Application

To stop the application:
```bash
docker compose down
```

## Database

The application uses MySQL database with the following default configuration:
- Database Name: cyberattack_db
- User: cyberuser
- Password: cyberpass

These settings can be modified in the `docker-compose.yml` file.

## Contributing

1. Fork the repository
2. Create your feature branch
3. Commit your changes
4. Push to the branch
5. Create a new Pull Request



