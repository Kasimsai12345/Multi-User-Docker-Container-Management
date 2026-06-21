# Multi-User Docker-Based Web Application Deployment with Persistent Storage Management

##Project Overview

This project demonstrates Linux Administration and Docker Container Management in a multi-user environment. Multiple Linux users were created and assigned different Docker-related responsibilities. A custom Docker image was built using Dockerfile and deployed as a web application. Docker volumes were implemented to provide persistent storage and verify data availability even after container deletion.

## Project Structure

```text
Multi-User-Docker-Container-Management
│
├── Commands
│   ├── docker_commands.txt
│   └── linux_commands.txt
│
├── Dockerfile
├── index.html
├── README.md
│
├── Documentation
│   └── Full_Docker_Project_Documentation.docx
│
└── Screenshots
    ├── user_creation.png
    ├── docker_installation.png
    ├── image_creation.png
    ├── container_creation.png
    ├── volume_creation.png
    ├── volume_mapping.png
    └── persistence_verification.png
```

## Features

* Linux User Administration
* SSH Configuration
* Docker Installation and Configuration
* Docker Group Permission Management
* Custom Docker Image Creation
* Docker Container Deployment
* Container Monitoring and Operations
* Docker Volume Creation
* Docker Volume Mapping
* Persistent Storage Verification

## Technologies Used

* Linux
* Docker
* Dockerfile
* HTML
* SSH
* Docker Volumes

## Tasks Performed

### Task 1 - Docker Image Management

Created a custom Docker image named **suresh** using Dockerfile and deployed a web application.

### Task 2 - Container Creation

Created a Docker container named **vks** using the custom image and deployed the application.

### Task 3 - Container Monitoring

Monitored container status, logs, and resource utilization using Docker commands.

### Task 4 - Container Operations

Performed container lifecycle operations such as start, stop, and restart.

### Task 5 - Docker Volume Creation

Created a Docker volume named **abcbank** and verified its storage location.

### Task 6 - Volume Mapping

Attached the Docker volume to container **vks2** using the mount path **/project1**.

### Task 7 - Data Persistence Verification

Verified that application data remained available after container deletion and recreation.

## Project Outcome

* Successfully created and managed Linux users.
* Built and deployed a custom Docker image.
* Managed Docker containers in a multi-user environment.
* Implemented Docker volumes for persistent storage.
* Verified data persistence after container recreation.
