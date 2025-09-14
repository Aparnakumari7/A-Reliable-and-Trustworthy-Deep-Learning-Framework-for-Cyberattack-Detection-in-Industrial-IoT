Trustworthy and Reliable Deep Learning-Based Cyberattack Detection

A Django-based web application for detecting cyberattacks in Industrial IoT environments using deep learning techniques.
Features

    Deep learning-based cyberattack detection
    User authentication system
    Real-time attack prediction
    Interactive data visualization
    Download predicted datasets
    View attack type ratios and statistics
    Remote user and service provider interfaces

Prerequisites

    Docker Desktop

Quick Start

    Clone or download this repository
    Open terminal in the project directory
    Run the application using Docker:

docker compose up

    Access the application at: http://localhost:8000

Project Structure

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

Technology Stack

    Python 3.9
    Django 4.2+
    TensorFlow
    MySQL
    NumPy
    Pandas
    Scikit-learn
    Matplotlib
    Seaborn

Development

To modify the application:

    Make changes to the code
    Rebuild and restart containers:

docker compose up --build

Stopping the Application

To stop the application:

docker compose down

Database

The application uses MySQL database with the following default configuration:

    Database Name: cyberattack_db
    User: cyberuser
    Password: cyberpass

These settings can be modified in the docker-compose.yml file.
Contributing

    Fork the repository
    Create your feature branch
    Commit your changes
    Push to the branch
    Create a new Pull Request
