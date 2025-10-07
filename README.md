### EMart Microservices Application (Dockerized | Full-Stack Project)

*Description:

Developed and deployed a containerized microservices-based EMart application using **Docker Compose** to orchestrate multiple interconnected services. The system architecture is built with an **Angular** frontend, **Node.js** (Emart API) and **Java** (Books API) backend services, and both **MongoDB** and **MySQL** databases, all managed through an **Nginx API Gateway**.

*Architecture Overview:

**Frontend:** Angular client served through Nginx.
**API Gateway:** Nginx routes client requests — `/api` directed to the Node.js Emart service and `/webapi` to the Java Books service.
*Backend Services:

**Emart API (Node.js + Express):** Handles user, product, and order-related operations, connected to **MongoDB**.
**Books API (Java + Spring Boot):** Manages book catalog and related data, connected to **MySQL**.
*Databases:

**MongoDB** for non-relational data storage (Emart service).
**MySQL** for relational data management (Books service).
**Containerization:** Each service (Angular, Node.js, Java, MongoDB, MySQL, Nginx) is dockerized and managed using Docker Compose for seamless deployment and scalability.
**Repository:** Complete source code and configuration files (Dockerfiles, docker-compose.yml, etc.) are publicly available on GitHub.

*Key Technologies:
Docker, Docker Compose, Angular, Node.js, Express.js, Java, Spring Boot, MongoDB, MySQL, Nginx
