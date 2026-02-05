logging : 
<img width="1366" height="768" alt="logging" src="https://github.com/user-attachments/assets/87b85b5e-6ba7-434f-b3b5-20383ddef027" />
docker image building: 
<img width="1366" height="720" alt="Docker_image_building" src="https://github.com/user-attachments/assets/be08e2fd-eaef-4115-a59c-7ecf55395ab3" />
postgres :
<img width="1366" height="720" alt="postgres" src="https://github.com/user-attachments/assets/1f0fc8f3-98b2-4a2b-afa8-fb1b091019b3" />
running containers : 
<img width="1366" height="720" alt="running_containers" src="https://github.com/user-attachments/assets/cc411ad6-b30f-451e-a4d8-3006a4358d70" />
This repository contains my Docker assignment for the Data Engineering course. The assignment demonstrates:

Docker Images & Containers: Building and running containers for various applications.
Docker Compose: Setting up a multi-container environment easily.
Volumes: Persisting data for PostgreSQL databases.
PostgreSQL Integration: Configuring a database container and connecting it with other services.
Practical Commands: Examples of docker run, docker exec, docker compose up, and resource management.

This project helps in understanding how to create, manage, and orchestrate containers in a local development environment.


<img width="1366" height="768" alt="Screenshot 2026-02-05 130042" src="https://github.com/user-attachments/assets/8f8f4ded-4c5b-4d0c-a623-2c41ab6fda04" />
<img width="1366" height="768" alt="Screenshot 2026-02-05 130450" src="https://github.com/user-attachments/assets/c95a2a2c-f6d4-4c1d-8170-b47b4780e69a" />
This demonstrates a multi-container Docker application using Flask and Redis. The Flask web application runs inside a Docker container and connects to a Redis container to maintain a persistent visitor counter. A custom Docker network is used to enable inter-container communication, and a Docker volume ensures Redis data persistence across container restarts.
Technologies Used
Docker
Python Flask
Redis
Docker Networking
Docker Volumes
