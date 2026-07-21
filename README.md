# Java Web Application CI/CD Pipeline

## Overview

This project demonstrates an end-to-end Continuous Integration and Continuous Deployment (CI/CD) pipeline for a Java web application using Jenkins, Maven, Apache Tomcat, GitHub, and AWS EC2.

## Architecture

Developer
↓
GitHub
↓
Jenkins
↓
Maven Build
↓
WAR Artifact
↓
SSH Deployment
↓
Apache Tomcat
↓
Live Web Application

## Tech Stack

- AWS EC2
- Amazon Linux 2023
- Jenkins
- Maven
- Git
- GitHub
- Apache Tomcat 10
- Java 21
- Linux
- SSH

## Features

- Automated source code checkout from GitHub
- Maven build automation
- WAR artifact generation
- Automated deployment to Apache Tomcat
- Jenkins Freestyle CI/CD Pipeline
- SSH-based deployment

## Project Workflow

1. Developer pushes code to GitHub
2. Jenkins clones the repository
3. Maven builds the WAR file
4. Jenkins transfers the WAR to Tomcat
5. Tomcat deploys the application automatically

## Challenges Solved

- Security Group configuration
- Tomcat installation and configuration
- Tomcat Manager authentication
- Java version compatibility
- Maven build issues
- GitHub authentication
- Jenkins executor issue
- SSH deployment configuration
- Branch configuration (main/master)

## Future Improvements

- Jenkins Pipeline (Jenkinsfile)
- GitHub Webhooks
- Docker
- Kubernetes
- Terraform
