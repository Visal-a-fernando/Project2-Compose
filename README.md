# Automating CI/CD with Dockerized Jenkins for Node.js Web Application

## Overview
This project demonstrates a complete CI/CD pipeline using **Jenkins**, **Docker**, and **Docker-in-Docker (DinD)**. It automates the process of building, testing, and securing a Node.js web application, integrating tools such as **Snyk** for security vulnerability scanning.

## Project Structure
- **Dockerized Jenkins Setup**: Jenkins is containerized using Docker and connects to Docker-in-Docker for managing Docker containers.
- **Pipeline Configuration**: The Jenkins pipeline builds the Node.js app, installs dependencies, runs tests, and performs a security scan.
- **Security Integration**: Includes Snyk for detecting vulnerabilities during the pipeline.

## Technologies Used
- **Jenkins**: For automating CI/CD processes.
- **Docker**: Containerizes Jenkins and supports running Docker commands inside Jenkins.
- **Docker Compose**: Manages multi-container Docker applications.
- **Node.js**: The application that is built and tested in the pipeline.
- **Snyk**: Scans for security vulnerabilities.

## Prerequisites
- Docker and Docker Compose installed on your machine.
- Node.js application code (forked or cloned repository).
- GitHub account for storing repositories.
- Snyk account and API token.

## Getting Started
1. **Clone the Project**  
   Clone this repository to your local machine:
   ```bash
   git clone https://github.com/Visal-a-fernando/Project2-Compose.git
