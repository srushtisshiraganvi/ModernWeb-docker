# 🌐 Static Web Application – Docker + Nginx Deployment

This project demonstrates how to deploy a **static web application** (HTML, CSS, JS) using **Docker** and **Nginx**.  
It uses a simple `Dockerfile` and `docker-compose.yml` setup to serve the web page efficiently.

---

## 🚀 Features
- Lightweight Nginx-based Docker container  
- Simple and fast setup using Docker Compose  
- Port mapping for easy local testing  
- Clean deployment structure  

---

## 🧱 Project Structure
.
├── Dockerfile
├── docker-compose.yml
└── index.html


---

## ⚙️ Installation & Setup

### Step 1: Install Docker and Docker Compose
Run the following commands:
`bash
sudo apt update
sudo apt install docker.io -y
sudo apt install docker-compose -y `

Step 2: Build and Run the Application
`docker-compose up --build `

Access the App
Once the build completes, open your browser and visit:
[http://localhost:8000](http://<your-public-IP>:8000
)

You’ll see your static web page running inside a Docker container served by Nginx 🚀
