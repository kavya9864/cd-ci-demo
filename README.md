# cd-ci-demo
# 🚀 CI/CD Pipeline with GitHub Actions & Docker

A complete **CI/CD pipeline** for a containerized application using **GitHub Actions**, **Docker**, and local deployment via **Minikube** or a local VM. This setup automatically builds the Docker image, runs tests, and pushes the image to **Docker Hub**.

---

## 🎯 Objective

- Automate build, test, and deployment using GitHub Actions.
- Containerize the app with Docker.
- Push image to Docker Hub.
- Deploy locally using Minikube or any local VM.

---

## ⚙️ Tools Used

- GitHub Actions (CI/CD)
- Docker & Docker Compose
- Docker Hub (image registry)
- Minikube / Local VM (for deployment)
- Bash & YAML for workflow scripts

---

## 🧱 Project Structure
ci-cd-pipeline/
├── app/ # Application code
│ ├── app.py
│ └── requirements.txt
├── Dockerfile # Docker build file
├── docker-compose.yml # Optional for multi-service apps
├── .github/
│ └── workflows/
│ └── ci-cd.yml # GitHub Actions workflow
├── README.md

Using Docker Compose
docker-compose up --build

🤖 GitHub Actions Workflow
Location
.github/workflows/ci-cd.yml
![cdci](https://github.com/user-attachments/assets/f9a2773a-1259-4c40-a787-4e287b158a92)

Tasks Performed
Install dependencies

Run tests

Build Docker image
![cd ci demo](https://github.com/user-attachments/assets/d943e83c-200e-48f5-a5f8-bd11daa4812b)

Push image to Docker Hub

📦 CI/CD Workflow Result
✅ GitHub Actions successfully builds the image and pushes to Docker Hub on every push to main.


![proj 4](https://github.com/user-attachments/assets/ecbd710c-027f-4789-8437-a71568790e54)

📜 License
This project is open-source and available under the MIT License.

🙌 Contributors
Kavya9864



