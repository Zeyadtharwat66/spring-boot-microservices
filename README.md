# Spring Boot Microservices

A backend project demonstrating a microservices architecture using **Java** and **Spring Boot**.

The project is divided into independent services for doctor, patient, and payment functionality.

## 🚀 Technologies

* Java
* Spring Boot
* Maven
* RESTful APIs
* Microservices

## 📁 Project Structure

```text
spring-boot-microservices/
│
├── doctor/
├── patient/
├── payment/
└── README.md
```

Each service has its own Maven configuration, application configuration, source code, and tests.

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/Zeyadtharwat66/spring-boot-microservices.git
```

Navigate to the project:

```bash
cd spring-boot-microservices
```

Build the individual services using Maven.

For example:

```bash
cd doctor
./mvnw spring-boot:run
```

On Windows:

```powershell
.mvnw.cmd spring-boot:run
```

Repeat the process for the other services.

## ▶️ Running the Project

The project contains three independent Spring Boot applications:

* **Doctor Service**
* **Patient Service**
* **Payment Service**

Each service can be started independently.

## 📌 Main Features

* Independent Spring Boot services
* RESTful API communication
* Separation of business responsibilities
* Independent service configuration
* Maven-based service projects

## 🛠️ Architecture

The project follows a service-based architecture:

```text
        ┌───────────────┐
        │  Doctor       │
        │  Service      │
        └───────────────┘

        ┌───────────────┐
        │  Patient      │
        │  Service      │
        └───────────────┘

        ┌───────────────┐
        │  Payment      │
        │  Service      │
        └───────────────┘
```

Each service is developed and configured independently.

## 🔮 Future Improvements

* Service discovery
* API gateway
* Centralized configuration
* Inter-service communication
* Docker containerization
* Distributed tracing
* Authentication and authorization

## 👨‍💻 Author

**Zeyad Tharwat**

## 📄 License

This project is for learning and development purposes.
