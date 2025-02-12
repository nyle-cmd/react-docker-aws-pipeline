# **React Docker AWS CI/CD Deployment**  

Automated deployment pipeline for a **React application** using **Docker, GitHub Actions, and AWS Elastic Beanstalk**.  

## **Features**
- 🐳 **Dockerized React app** for consistent builds  
- 🔄 **CI/CD pipeline with GitHub Actions** for automated deployments  
- ☁️ **AWS Elastic Beanstalk** for scalable hosting  
- 📂 **S3 storage for deployment artifacts**  

## **Tech Stack**
- **React** (Frontend)  
- **Docker** (Containerization)  
- **GitHub Actions** (CI/CD Automation)  
- **AWS Elastic Beanstalk** (Hosting)  
- **AWS S3** (Storage)  

## **Setup & Deployment**  

### **1. Clone the repository**  
```sh
git clone https://github.com/your-username/react-docker-aws-cicd.git
cd react-docker-aws-cicd
```

### **2. Run Locally with Docker**  
```sh
docker-compose up --build
```
App should be available at **http://localhost:80**.

### **3. Deploy to AWS Elastic Beanstalk**
Push to GitHub, and the CI/CD pipeline will automatically deploy:
```sh
git push origin main
```

## **Project Structure**
```
📦 react-docker-aws-cicd
 ┣ 📂 src/                 # React source files
 ┣ 📜 Dockerfile           # Multi-stage Docker build
 ┣ 📜 docker-compose.yml   # Docker Compose setup
 ┣ 📜 .github/workflows/   # GitHub Actions CI/CD
 ┣ 📜 README.md            # Documentation
```

## **License**
MIT License  
