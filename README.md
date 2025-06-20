# Collabrix Backend 🛠️

Welcome to the Collabrix Backend repository! This project serves as the backend for Collabrix, a project management platform designed to streamline collaboration and enhance productivity. The backend is built using Spring Boot and is containerized with Docker, making it easy to deploy and manage. It integrates with MySQL for data storage and features user management, authentication, and email notifications.

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Deployment](#deployment)
- [Contributing](#contributing)
- [License](#license)
- [Links](#links)

## Features

- **User Management**: Manage user accounts and roles effectively.
- **Authentication**: Secure user login and registration processes.
- **Email Notifications**: Send notifications to users for various events.
- **REST API**: Access backend functionalities via a simple RESTful interface.
- **Docker Support**: Easily deploy the application using Docker containers.
- **MySQL Integration**: Store data reliably with MySQL.

## Technologies Used

- **Java**: The primary programming language for backend development.
- **Spring Boot**: Framework used to create the backend application.
- **MySQL**: Database management system for data storage.
- **Docker**: Containerization platform for easy deployment.
- **Java Mail**: For sending email notifications.
- **REST API**: For communication between frontend and backend.

## Getting Started

To get started with the Collabrix Backend, follow these steps:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Nabillawilma/Collabrix-Backend.git
   ```

2. **Navigate to the Project Directory**:
   ```bash
   cd Collabrix-Backend
   ```

3. **Build the Project**:
   Ensure you have Maven installed, then run:
   ```bash
   mvn clean install
   ```

4. **Set Up Environment Variables**:
   Create a `.env` file in the root directory and configure your database and email settings.

5. **Run the Application**:
   You can run the application locally using:
   ```bash
   mvn spring-boot:run
   ```

## Usage

Once the application is running, you can access the REST API endpoints. Below are some common endpoints:

- **User Registration**: `POST /api/users/register`
- **User Login**: `POST /api/users/login`
- **Get All Users**: `GET /api/users`
- **Send Email Notification**: `POST /api/notifications/send`

Refer to the API documentation for more details on the available endpoints and their usage.

## Deployment

To deploy the Collabrix Backend, you can use Docker. Follow these steps:

1. **Build the Docker Image**:
   ```bash
   docker build -t collabrix-backend .
   ```

2. **Run the Docker Container**:
   ```bash
   docker run -d -p 8080:8080 collabrix-backend
   ```

3. **Access the Application**:
   Open your web browser and navigate to `http://localhost:8080`.

For cloud deployment, consider using platforms like Render or Railway. Follow their documentation for detailed deployment steps.

## Contributing

We welcome contributions! To contribute to the Collabrix Backend, please follow these steps:

1. **Fork the Repository**: Click on the "Fork" button at the top right corner of the page.
2. **Create a Branch**: 
   ```bash
   git checkout -b feature/YourFeature
   ```
3. **Make Your Changes**: Implement your feature or fix a bug.
4. **Commit Your Changes**: 
   ```bash
   git commit -m "Add your message here"
   ```
5. **Push to Your Branch**: 
   ```bash
   git push origin feature/YourFeature
   ```
6. **Create a Pull Request**: Go to the original repository and click on "New Pull Request".

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Links

For releases and updates, please visit our [Releases section](https://github.com/Nabillawilma/Collabrix-Backend/releases). Here, you can download the latest version of the backend and execute it.

You can also check the [Releases section](https://github.com/Nabillawilma/Collabrix-Backend/releases) for any updates or new features added to the Collabrix Backend.

![Collabrix Backend](https://img.shields.io/badge/Collabrix%20Backend-v1.0-blue.svg)
![Docker](https://img.shields.io/badge/Docker-Enabled-green.svg)
![Java](https://img.shields.io/badge/Java-11-orange.svg)
![MySQL](https://img.shields.io/badge/MySQL-8.0-yellow.svg)

Thank you for your interest in the Collabrix Backend! We hope you find it useful for your project management needs.