# Dockerized Python Flask App

## 🚀 Objective

A simple Python Flask application containerized using Docker and deployed on AWS EC2.

## 📝 Files

- app.py: Flask application
- requirements.txt: Python dependencies
- Dockerfile: Docker image instructions

## 💻 How to Build and Run

```bash
docker build -t flask-app .
docker run -p 5000:5000 flask-app

## screenshots 

### EC2 instance dashboard.png
![EC2_instance_dashboard](screenshots/EC2_instance_dashboard.png)

### SSH connection.png
![SSH_connection](screenshots/SSH_connection.png)

### Docker build and run commands.png
![Docker_build_and_run_commands](screenshots/Docker_build_and_run_commands.png)

### Browser output verifying deployment.png
![Browser_output_verifying_deployment](screenshots/Browser_output_verifying_deployment.png)
