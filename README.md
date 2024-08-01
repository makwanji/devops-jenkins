# 🚀 Jenkins in Docker with Docker Compose

Welcome to the Jenkins in Docker with Docker Compose project! This project sets up a Jenkins server using Docker Compose, and includes a Jenkins pipeline to clone a specific repository, create a Docker image, and push it to Docker Hub. 🐋

## 📝 Table of Contents

- [Prerequisites](#prerequisites)
- [Setup](#setup)
- [Jenkins Pipeline](#jenkins-pipeline)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## ✅ Prerequisites

Before you begin, ensure you have the following installed:

- Docker 🐳
- Docker Compose 🐙

## ⚙️ Setup

1. **Update hostfile**:

    ```bash
    127.0.0.1 mylabs.com
    ```

1. **Clone the Repository**:

    ```bash
    git clone <your-repo-url>
    cd <your-repo-directory>
    ```

3. **Start Jenkins**:

   ```bash
   docker-compose up -d
   ```

4. **Access Jenkins**:

   Open your browser and navigate to `http://mylabs.com:8080`. Use the initial admin password found in the Jenkins container logs to set up your admin user.

