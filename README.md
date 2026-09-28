# ☁️ CloudSpace

A modern responsive web application deployed on **AWS EC2 using Docker**.

## 🚀 Architecture

```text
VS Code
   ↓
Git + GitHub
   ↓
AWS EC2
   ↓
Docker
   ↓
Nginx
   ↓
CloudSpace 🌐
```

## 🛠️ Tech Stack

* HTML5
* CSS3
* JavaScript
* Nginx
* Docker
* Git & GitHub
* AWS EC2
* Ubuntu Linux

## 📁 Project Structure

```text
cloudspace/
├── index.html
├── style.css
├── Dockerfile
└── README.md
```

## 🐳 Run with Docker

Build the image:

```bash
docker build -t cloudspace-app .
```

Run the container:

```bash
docker run -d -p 8080:80 --name cloudspace-container cloudspace-app
```

Open:

```text
http://localhost:8080
```

## ☁️ Deploy on AWS EC2

Clone the repository:

```bash
git clone https://github.com/Aryan-a1212/cloudspace.git
cd cloudspace
```

Build and run:

```bash
docker build -t cloudspace-app .
docker run -d -p 80:80 --name cloudspace-container cloudspace-app
```

Access the application using the EC2 Public IPv4 address:

```text
http://<EC2-PUBLIC-IP>
```

## 🎯 Project Objective

This project demonstrates the complete workflow of:

**Develop → Git → GitHub → Docker → AWS EC2 → Deploy**

## 🔮 Future Improvements

* GitHub Actions CI/CD
* AWS CloudWatch monitoring
* Terraform
* Prometheus & Grafana
* Kubernetes
* HTTPS with custom domain

## 👨‍💻 Author

**Aryan Maheshwari**

B.Tech Computer Science Engineering
Linux | AWS | Docker | Cloud | DevOps
# ☁️ CloudSpace

A modern responsive web application deployed on **AWS EC2 using Docker**.

## 🚀 Architecture

```text
VS Code
   ↓
Git + GitHub
   ↓
AWS EC2
   ↓
Docker
   ↓
Nginx
   ↓
CloudSpace 🌐
```

## 🛠️ Tech Stack

* HTML5
* CSS3
* JavaScript
* Nginx
* Docker
* Git & GitHub
* AWS EC2
* Ubuntu Linux

## 📁 Project Structure

```text
cloudspace/
├── index.html
├── style.css
├── Dockerfile
└── README.md
```

## 🐳 Run with Docker

Build the image:

```bash
docker build -t cloudspace-app .
```

Run the container:

```bash
docker run -d -p 8080:80 --name cloudspace-container cloudspace-app
```

Open:

```text
http://localhost:8080
```

## ☁️ Deploy on AWS EC2

Clone the repository:

```bash
git clone https://github.com/Aryan-a1212/cloudspace.git
cd cloudspace
```

Build and run:

```bash
docker build -t cloudspace-app .
docker run -d -p 80:80 --name cloudspace-container cloudspace-app
```

Access the application using the EC2 Public IPv4 address:

```text
http://<EC2-PUBLIC-IP>
```

## 🎯 Project Objective

This project demonstrates the complete workflow of:

**Develop → Git → GitHub → Docker → AWS EC2 → Deploy**

## 🔮 Future Improvements

* GitHub Actions CI/CD
* AWS CloudWatch monitoring
* Terraform
* Prometheus & Grafana
* Kubernetes
* HTTPS with custom domain

## 👨‍💻 Author

**Aryan Maheshwari**

B.Tech Computer Science Engineering
Linux | AWS | Docker | Cloud | DevOps
