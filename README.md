# 🌐 AWS Static Portfolio Website Deployment

![AWS](https://img.shields.io/badge/AWS-S3-orange)
![GitHub Actions](https://img.shields.io/badge/GitHub-Actions-blue)
![HTML](https://img.shields.io/badge/HTML-5-orange)
![CSS](https://img.shields.io/badge/CSS-3-blue)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6-yellow)

## 📌 Project Overview

This project demonstrates how to deploy a static portfolio website using Amazon S3 and automate deployments using GitHub Actions.

Every time changes are pushed to the **main** branch, GitHub Actions automatically uploads the latest website files to the S3 bucket.

---

# 🚀 Architecture

<p align="center">

<!-- INSERT ARCHITECTURE DIAGRAM HERE -->

</p>

---

# 📸 Project Screenshots

## Home Page

![alt text](<./Screenshot/Screenshot 2026-07-16 200121.png>)

---

## AWS S3 Bucket

![alt text](<./Screenshot/Screenshot 2026-07-16 210315.png>)

---

## Static Website Hosting

![alt text](<./Screenshot/Screenshot 2026-07-16 210907.png>)

---

## GitHub Repository

![alt text](<./Screenshot/Screenshot 2026-07-16 211045.png>)

---

## GitHub Actions Workflow

![alt text](<./Screenshot/Screenshot 2026-07-16 211241.png>)

---

## Live Website

![alt text](<./Screenshot/Screenshot 2026-07-16 211414.png>)

---

# 🛠 Technologies Used

- HTML5
- CSS3
- JavaScript
- Git
- GitHub
- GitHub Actions
- Amazon S3
- IAM

---

# ⚙️ GitHub Actions Workflow

The workflow automatically:

- Checks out the repository
- Configures AWS credentials securely using GitHub Secrets
- Deploys website files to Amazon S3
- Deletes removed files from the bucket

---

# 📂 Project Structure

```text
.
├── .github
│   └── workflows
│       └── main.yml
├── index.html
├── style.css
├── script.js
└── README.md
```

---

# 🔒 GitHub Secrets

The following secrets are configured in GitHub:

- AWS_ACCESS_KEY_ID
- AWS_SECRET_ACCESS_KEY

---

# ☁ AWS Services Used

- Amazon S3
- IAM
- GitHub Actions

---

# 🎯 Skills Demonstrated

- AWS S3 Static Website Hosting
- CI/CD using GitHub Actions
- Git & GitHub
- Cloud Deployment
- IAM Security
- Static Website Hosting
- Version Control
- Infrastructure Automation

---

# 📖 Learning Outcomes

Through this project, I learned:

- Hosting a static website on Amazon S3
- Configuring Static Website Hosting
- Managing IAM credentials securely
- Creating GitHub Actions workflows
- Automating deployments
- Working with GitHub Secrets
- Implementing CI/CD pipelines

---

# 👨‍💻 Author

**Ayush Bhardwaj**

AWS Cloud Engineer

LinkedIn: [Ayushbhardwaj001](https://www.linkedin.com/in/ayushbhardwaj001/)

GitHub: [AyushBhardwaj007](https://github.com/AyushBhardwaj0007)

Email: ayushbharwaj@gmail.com