# What is Docker ?
Docker allows you to package an application with its dependencies so it runs consistently across different environments.
Resolves "Works on my machine" issue

## Image 
it acts as blueprint for docker container, instructions how to create container

## Container
running instance of Image, this is a actual running app

## Dockerfile
it's a text file that says, which base software to use, what files to copy, how to start the app

## Port mapping
Port mapping connects a port inside the container to a port on your laptop.
It creates a bridge between your machine(host) and container
<img width="993" height="462" alt="image" src="https://github.com/user-attachments/assets/1abfdb94-45a6-4cdc-a537-7e2c344c42fd" />
<img width="1006" height="521" alt="image" src="https://github.com/user-attachments/assets/c53dc007-5883-42ff-b68c-476080e3b14f" /> 

## Docker hub
Docker Hub is a cloud-based registry service that allows developers to store, share, and manage Docker images.
Docker Hub is for sharing runnable applications, not source code collaboration.

## Docker Volumes
A Docker volume is a persistent storage mechanism used to store data outside containers so that data is not lost when containers are stopped or removed
<img width="966" height="310" alt="image" src="https://github.com/user-attachments/assets/07e67eef-139b-43bf-987f-52ca5aa70e78" />
<img width="988" height="203" alt="image" src="https://github.com/user-attachments/assets/94d0b8a8-2654-41d4-8c73-e883e07e7bca" />





## docker-compose.yml
Docker Compose is a manager that starts multiple Docker containers together using one file and one command.
think it as remote control for many containers
it's a configuration file that tells docker
1) Which containers are needed
2) How they connect
3) Which ports to use
4) Environment variables
5) Startup order

<img width="1015" height="407" alt="image" src="https://github.com/user-attachments/assets/6545f73e-6926-407d-a968-48127ed16acb" />

## Docker compose watch
Docker Compose Watch is a development feature that monitors source code changes and automatically syncs or rebuilds containers, enabling faster feedback during local development.
Think of Compose Watch like Live Reload / Hot Reload:
<img width="992" height="409" alt="image" src="https://github.com/user-attachments/assets/bbdb298f-5853-40da-b36d-6130e2ab48a3" />
<img width="974" height="334" alt="image" src="https://github.com/user-attachments/assets/6e2d421a-5d0d-40c4-9eee-8366563f6b9e" />
<img width="1203" height="455" alt="image" src="https://github.com/user-attachments/assets/c5e8034c-3c4f-458b-a21d-183cd9c8d347" />




## Screenshots
<img width="1914" height="838" alt="image" src="https://github.com/user-attachments/assets/efd2e48e-512e-42ae-8f38-8a054fd34a18" />
