# CV DevOps Project

A simple DevOps project to host and serve my personal CV as a static HTML page using Docker and Kubernetes.
## 🚀 Tech Stack

- 🐳 Docker
- ☸️ Kubernetes
- 🧰 Nginx (as web server)
- 💻 HTML/CSS
- 🔗 GitHub

## 🔗 Useful Links
## 🔗 Useful Links

- GitHub Repo: [https://github.com/mohammadalkhatib97/cv-devops](https://github.com/mohammadalkhatib97/cv-devops)
- docker hub:  mohammadalkhatib97/project-cv1:latest

## 🛠️ How to Build and Push Docker Image

```bash
# Build Docker image locally (تأكد أنك داخل مجلد المشروع)
docker build -t mohammadalkhatib97/project-cv1:latest .

# تسجيل الدخول إلى Docker Hub (مرة واحدة فقط)
docker login

# رفع الصورة إلى Docker Hub
docker push mohammadalkhatib97/project-cv1:latest
kubectl apply -f deployment.yaml
kubectl apply -f service.yaml
kubectl get pods
kubectl get services

