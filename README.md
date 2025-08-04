# CI/CD Pipeline with GitHub Actions - Node.js App

This project demonstrates how to automate code deployment using GitHub Actions and Docker.

## 🔧 Tech Stack

- Node.js
- Docker
- GitHub Actions
- DockerHub

## 📦 Project Structure

```
ci-cd-nodejs-app/
├── app/
│   ├── app.js
│   └── package.json
├── Dockerfile
├── .github/
│   └── workflows/
│       └── main.yml
└── README.md
```

## 🚀 Steps to Run

1. Fork this repo and clone it.
2. Create a public DockerHub repo.
3. In GitHub → Settings → Secrets → Actions:
   - `DOCKER_USERNAME`
   - `DOCKER_PASSWORD`
4. Push to `main` branch → GitHub Action will:
   - Build Docker image
   - Push it to DockerHub

## 🔗 DockerHub Output

Image will be available at:
```
docker pull your-docker-username/nodejs-demo:latest
```

## 📞 Author

Abhay Rajak – [Your Email or GitHub]
