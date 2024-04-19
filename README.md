# Docker + Kuberbetes

A project do display the docker and kubernetes skills for containerization and orchestration of a full stack app.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)

## Introduction

This project is aimed at manage your tasks. It utilizes Docker and Kubernetes for containerization and orchestration, React for the frontend, and Node.js for the backend.

## Features

- A simple application to manage your tasks.

## Prerequisites

Before running this project locally or deploying it, ensure you have the following prerequisites installed:

- Kubernetes (minikube and kubectl)

## Installation

1. Clone the repository:

```bash
git clone https://github.com/theUmeshC/docker-kubernities.git
```

2. Navigate to Kubernities folder

``` bash
    cd kubernetes
```

3. run the services and deployements

``` bash
    kubectl apply -f auth-service.yaml -f auth-deployment.yaml -f users-service.yaml -f users-deployment.yaml -f tasks-service.yaml -f tasks-deployment.yaml -f frontend-service.yaml -f frontend-deployment.yaml
```

4. minikube serve frontend server

``` bash
    minikube serve frontend-service
```
