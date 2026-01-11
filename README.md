# Dockerized Web App on AWS EC2

This project demonstrates deploying a Dockerized web application on AWS EC2.

## What I did
- Installed Docker on EC2
- Created Dockerfile using Nginx
- Built Docker image
- Ran container exposing port 80
- Accessed application via public IP

## Tech Stack
- AWS EC2
- Docker
- Nginx
- Linux

docker file 
FROM nginx:latest
COPY index.html /usr/share/nginx/html/index.html


## Notes
- Containers can be restarted easily without reinstalling services
- Docker makes deployments faster and consistent

