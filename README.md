# 🚀 o2h DevOps Assessment

This repository contains the solution for the **o2h DevOps Assessment**, demonstrating fundamental DevOps concepts including Git, Linux administration, Docker containerization, CI/CD automation using GitHub Actions, troubleshooting techniques, and Bash scripting.

---

##  Project Overview

The objective of this assessment is to showcase practical knowledge of:

* Git & GitHub
* Linux Commands
* Docker
* CI/CD Pipelines
* Troubleshooting
* Shell Scripting

---

## 📂 Repository Structure

```text
o2h-devops-assessment
│
├── .github/
│   └── workflows/
│       └── workflow.yml
├── Dockerfile
├── README.md
├── app.js
├── Linux_Commands.md
├── Troubleshooting.md
├── script.sh
├── package.json
├── package-lock.json
├── screenshots/
└── .gitignore
```

---

## ✅ Task 1: Git & GitHub

* Initialized a Git repository.
* Created and organized the project structure.
* Committed and pushed code to GitHub.

---

## ✅ Task 2: Linux Administration

Documented commonly used Linux commands including:

* Current user information
* Disk usage
* Memory usage
* Finding log files
* Creating backup directories
* Compressing directories

File:

```text
Linux_Commands.md
```

---

## ✅ Task 3: Dockerization

Created a simple Node.js application using Express and containerized it using Docker.

### Build Docker Image

```bash
docker build -t o2h-app .
```

### Run Container

```bash
docker run -p 3000:3000 o2h-app
```

### Access Application

```text
http://localhost:3000
```

Expected response:

```text
Hello from o2h DevOps Assessment
```

---

## ✅ Task 4: CI/CD Pipeline

Implemented a GitHub Actions workflow that automatically:

1. Checks out the source code.
2. Sets up Node.js.
3. Installs dependencies.
4. Runs tests.
5. Builds the Docker image.

Workflow file:

```text
.github/workflows/workflow.yml
```

---

## ✅ Task 5: Troubleshooting

Documented common troubleshooting scenarios:

* Docker container exits immediately.
* Application works locally but not on the server.

File:

```text
Troubleshooting.md
```

---

## ⭐ Bonus Task: Bash Script

Implemented a shell script that:

* Creates a backup directory.
* Copies all `.txt` files.
* Displays a success message.

File:

```text
script.sh
```

---

## 🛠 Technologies Used

* Git
* GitHub
* Linux
* Node.js
* Express.js
* Docker
* GitHub Actions
* Bash Shell

---

## 📸 Screenshots

Relevant screenshots are available in the `screenshots/` directory.

---

## 📈 CI/CD Status

GitHub Actions pipeline successfully executes on every push to the `main` branch.

---

## 👨‍💻 Author

**Teja Marisetti**

GitHub: https://github.com/tejamarisetti

---

## 🎯 Outcome

This assessment demonstrates practical understanding of:

* Version Control
* Linux Administration
* Containerization
* Continuous Integration
* Troubleshooting
* Shell Scripting

---
