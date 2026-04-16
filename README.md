# Docker WAR Application Deployment

## Overview
This project demonstrates the deployment of a Java-based web application (WAR file) using Docker and AWS EC2. The application is containerized using Apache Tomcat and made accessible over the internet via an EC2 instance.

## Technologies Used
- Docker
- Apache Tomcat (v9)
- AWS EC2
- Docker Hub

## Project Structure
- Dockerfile
- app.war

## Dockerfile Configuration
- Uses Tomcat 9 as base image
- Removes default applications
- Deploys WAR file as ROOT application
- Exposes port 8080

## Deployment Steps
1. Built Docker image from WAR file
2. Tested container locally
3. Pushed image to Docker Hub
4. Pulled image on AWS EC2 instance
5. Ran container with port mapping (80 → 8080)
6. Configured security group to allow HTTP traffic

## Live Application
http://3.239.127.76

## Key Features
- Containerized deployment
- Cloud hosting using AWS
- Simplified web application deployment
- Scalable and portable architecture

## Conclusion
This project showcases the use of Docker for containerization and AWS EC2 for cloud deployment, enabling efficient and scalable hosting of web applications.
