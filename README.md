# Task-8-Deploy-a-Dockerized-Web-Application-on-the-Cloud
To understand *containerization* and *cloud-native deployment* by creating a *Docker image* of a simple web application and deploying it to a *cloud platform* (Google Cloud Run / AWS ECS / Azure Container Instances).

## 🧰 Tools Used

- Python 3.9

- Flask Framework

- Docker Desktop / CLI

- Google Cloud SDK (gcloud)

- Google Cloud Run

## 💻 Step 1: Create the Flask App
## 🐋 Step 2: Create a Dockerfile
## ⚙️ Step 3: Build and Run Locally
## ☁️ Step 4: Push to Google Container Registry
## 🚀 Step 5: Deploy to Google Cloud Run

## Output

#### Screenshot 1: Local Docker container running (localhost:8080)

#### Screenshot 2: Live deployed app on Google Cloud Run

## Key Learnings

- How to containerize a Flask app using Docker

- Understanding Docker images vs containers

- Using Google Container Registry & Cloud Run

- Deploying a serverless containerized app

## Cleanup

- To avoid extra charges, delete the service when finished:
  ```
  gcloud run services delete mycloudapp
```

