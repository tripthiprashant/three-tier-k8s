# Simple Blog App – AWS RDS Deployment

A full-stack blog application built for educational purposes, demonstrating CRUD operations using React.js, Node.js, Express.js, Docker, and AWS RDS MySQL.

## 🚀 Tech Stack

- **Frontend:** React.js, CSS3
- **Backend:** Node.js, Express.js
- **Database:** AWS RDS MySQL 8.4
- **Containerization:** Docker
- **Container Registry:** Docker Hub
- **Orchestration:** Kubernetes (kind)
- **CI/CD:** GitHub Actions
- **Architecture:** RESTful API

## 🏗️ Architecture

The application follows a three-tier architecture:

1. **Presentation Layer:** React frontend.
2. **Application Layer:** Node.js and Express REST API.
3. **Database Layer:** AWS RDS managed MySQL database.

### Application Workflow

- Users interact with the React frontend.
- The frontend communicates with the Express backend through REST APIs.
- The backend performs CRUD operations on the AWS RDS MySQL database.
- Database credentials are supplied through environment variables.

## ✨ Features

- ✅ Create, read, update, and delete blog posts.
- 📱 Responsive design for different devices.
- 🎨 Clean and intuitive user interface.
- 👤 Author attribution and timestamps.
- 📝 Simple text editor for content creation.
- 🔍 Post excerpts on the home page.
- ☁️ Managed database using AWS RDS.
- 🐳 Docker-based application deployment.
- ⚙️ Automated image build and push using GitHub Actions.

## 🛠️ Installation and Setup

### Prerequisites

- Node.js (v14 or higher)
- npm or yarn
- AWS account
- AWS RDS MySQL instance
- Docker
- Docker Hub account
- Kubernetes and kind (for Kubernetes deployment)

### 1. Clone the Repository

```bash
git clone <repository-url>
cd simple-blog-app
```

### 2. AWS RDS Database Setup

Create an AWS RDS MySQL instance with the following
