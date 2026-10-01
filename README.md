cd /home/masira/devops/nodejs-demo-app# Node.js Demo App

A simple Node.js application containerized using Docker as part of my DevOps internship task.

## 🚀 Project Overview

This project demonstrates how to:

* Create and run a Node.js application
* Install and manage dependencies using npm
* Write and run automated tests using Jest
* Create a Docker image using a Dockerfile
* Run the application inside a Docker container
* Map a Docker container port to the host machine
* Use Git and GitHub for version control

## 🛠️ Technologies Used

* Node.js
* npm
* Express.js
* Jest
* Supertest
* Docker
* Git
* GitHub
* Linux/WSL

## 📁 Project Structure

```text
nodejs-demo-app/
│
├── app.js
├── package.json
├── package-lock.json
├── Dockerfile
├── .dockerignore
├── .gitignore
└── test/
```

## ⚙️ Run the Application Locally

### 1. Clone the repository

```bash
git clone https://github.com/Masira-Shaikh02/nodejs-demo-app.git
cd nodejs-demo-app
```

### 2. Install dependencies

```bash
npm install
```

### 3. Run the application

```bash
node app.js
```

The application runs on port `3000`.

Open:

```text
http://localhost:3000
```

## 🧪 Run Tests

Run the automated tests using:

```bash
npm test
```

## 🐳 Run with Docker

### 1. Build the Docker image

```bash
docker build -t nodejs-demo-app .
```

### 2. Run the Docker container

```bash
docker run -p 3000:3000 nodejs-demo-app
```

### 3. Open the application

Open your browser and visit:

```text
http://localhost:3000
```

## 🔐 Docker Configuration

The project includes:

* `Dockerfile` — instructions for building the Docker image
* `.dockerignore` — prevents unnecessary files such as `node_modules` from being copied into the image
* `.gitignore` — prevents unnecessary or sensitive files from being committed to Git

## 📌 What I Learned

Through this project, I learned the basics of:

* Node.js application setup
* npm and package management
* Automated testing
* Docker images and containers
* Dockerfile creation
* Docker port mapping
* Linux/WSL environment
* Git version control
* GitHub repository management

## 👩‍💻 Author

**Masira Shaikh**

GitHub: [Masira-Shaikh02](https://github.com/Masira-Shaikh02)
