# Expense Tracker - DevOps CI/CD Project

## 📌 Project Overview
Expense Tracker is a PHP-based web application developed to manage and track daily expenses.  
This project was deployed using modern DevOps tools and practices including Docker, Jenkins, Terraform, GitHub, and AWS EC2.

---

## 🚀 Features
- Add expenses
- Edit expenses
- Delete expenses
- MySQL database integration
- Dockerized application deployment
- Jenkins CI/CD pipeline automation
- AWS EC2 cloud deployment
- Infrastructure provisioning using Terraform

---

## 🛠️ Technologies Used

### Frontend
- HTML
- CSS
- PHP

### Backend
- PHP
- MySQL

### DevOps Tools
- Docker
- Docker Compose
- Jenkins
- Terraform
- GitHub
- AWS EC2

---

## ☁️ AWS Deployment
The application was deployed on an AWS EC2 Ubuntu instance.

### EC2 Configuration
- Instance Type: t3.micro
- OS: Ubuntu 24.04
- Region: eu-north-1

---

## 🐳 Docker Setup

### Build Docker Image
```bash
docker build -t expense-tracker .
docker run -d -p 8080:80 expense-tracker
