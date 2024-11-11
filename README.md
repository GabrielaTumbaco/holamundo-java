# HolaMundo-Java ☕

This repository contains a simple Java program that prints "Hola Mundo" to the console. This example is useful for learning basic Java syntax and console output.

## Description ✍️

The program defines a `HolaMundo` class with a `main` method that prints a greeting message, "Hola Mundo", to the console when executed.

## Requirements

- **Java Development Kit (JDK)** 8 or higher
- **Git** to clone the repository

## How to Clone and Run

To clone this repository to your local machine, use the following commands:

```bash
git clone https://github.com/GabrielaTumbaco/holamundo-java.git
cd holamundo-java
```
## To run the program:

```bash
ruby frases.rb
```
## Dockerization 🐋
<ol>
  Step 1: Build the Docker Image

```bash

docker build -t holamundo .
```
  Step 2: Tag the Image

```bash

docker tag holamundo gltumbaco/holamundo:latest
```

  Step 3: Push Image to Docker Hub
```bash
docker push gltumbaco/holamundo:latest
```
</ol>

## Link to Docker Hub 👩‍💻

HolaMundo-Java on Docker Hub: https://hub.docker.com/repository/docker/gltumbaco/holamundo/general
