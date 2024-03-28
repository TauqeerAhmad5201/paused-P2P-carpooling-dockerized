# Paused-P2P-carpooling
Welcome to the Paused-P2P-Carpooling repository! Project aims to revolutionize the carpooling industry by leveraging blockchain technology. This project utilizes Docker and Docker Compose to manage a multi-container application. Follow the instructions below to get started.

## Prerequisites
Before you begin, ensure you have the following installed:

- Docker: If you haven’t already, install Docker.
- Docker Compose: If you haven’t already, install Docker Compose.

## Getting Started

1. Fork and Clone the Repository:

   ```
   git clone https://github.com/<your-username>/paused-P2P-carpooling-dockerized.git
   ```
2. Build and Run the Containers:

   ```
   docker compose up -d
   ```
Note: Make sure you're in ``paused-P2P-carpooling-dockerized`` folder. 

3. Wait for Services to Initialize: Depending on your project, some services (like databases) may take a moment to initialize. You can use the ``./wait-for-it`` script to wait for specific services to be ready. Modify the script as needed for your services.

4. Access Your Application:

   - Front-End: Navigate to ```http://localhost:3000```
   - Back-End: Navigate to ```http://localhost:4000```
   - MongoDB: Navigate to ```http://localhost:27017```

5. Credits: 

All the credits go the team of https://github.com/unmani-shinde/paused-P2P-carpooling for building the code and managing the stuffs. I just served as the ops-manager in the projet. 
