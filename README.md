# DevopsProject
Product Management Application

Product Management Application

This repository contains a Product Management web application with functionalities for managing products, categories, users, and roles. The application uses PostgreSQL for its database, is dockerized, and orchestrated using Docker Compose. It also includes CI/CD configuration with GitHub Actions and Kubernetes manifests for deployment.
Features

    Product Management: Add, update, delete, and view products.
    Category Management: Organize products into categories.
    User Management: Manage user accounts and their roles.
    Role-Based Access Control (RBAC): Assign roles to users for access control.
    PostgreSQL Integration: Persistent storage of data.
    Dockerized: Easily deployable with Docker.
    CI/CD Pipeline: Automated builds and deployments with GitHub Actions.
    Kubernetes Orchestration: Kubernetes manifests for seamless deployment.

Project Structure

    app/: Source code of the Product Management application.
    k8s/: Kubernetes manifests for deploying the application and database.
    Dockerfile: Dockerfile for building the application container.
    docker-compose.yml: Docker Compose file for running the application and database locally.
    .github/workflows/: GitHub Actions workflows for CI/CD.
