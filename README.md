# Cloud Resume Website — Serverless AWS Project

A fully serverless, cloud-hosted resume website designed to demonstrate practical experience with AWS infrastructure, backend development in Python, and modern web deployment practices.

## Live Website

https:d1rwhjcilhh6qo.cloudfront.net

---

## Project Overview

This project showcases a cloud-native resume website built using AWS services. The site is delivered globally over HTTPS using a CDN and includes a serverless backend that tracks visitor traffic in real time.

The goal of this project is to demonstrate hands-on experience with:

* Cloud architecture
* Serverless computing
* Infrastructure configuration
* Secure and scalable deployment

---

## Architecture

```
User Browser
     ↓
CloudFront (HTTPS + CDN)
     ↓
Amazon S3 (Static Website Hosting)

User Browser
     ↓
API Gateway (HTTP API)
     ↓
AWS Lambda (Python)
     ↓
Amazon DynamoDB (Visitor Counter)
```

---

## Tech Stack

### Frontend

* HTML5
* CSS3 (responsive, modern layout)

### Cloud & Backend

* **Amazon S3** – Static website hosting
* **Amazon CloudFront** – CDN and HTTPS delivery
* **AWS IAM** – Bucket policies and service permissions
* **AWS Lambda (Python)** – Serverless backend logic
* **Amazon DynamoDB** – NoSQL database for visitor tracking
* **Amazon API Gateway** – HTTP API integration

---

## Key Features

* Fully serverless architecture (no servers to manage)
* HTTPS enabled using CloudFront
* Real-time visitor counter powered by Python and DynamoDB
* Global content delivery with low latency
* Clean, professional, mobile-responsive design
* Infrastructure designed with scalability and cost efficiency in mind

---

## Security & Best Practices

* IAM policies configured to follow the principle of least privilege
* CloudFront used to securely deliver public content
* Backend services isolated behind API Gateway
* No hard-coded credentials in frontend or backend code

---

## Repository Structure

cloud-resume-website/
├── index.html
├── style.css
├── resume.pdf
└── README.md

---

## What This Project Demonstrates

* Ability to design and deploy cloud-based systems
* Practical experience with AWS core services
* Understanding of serverless architectures
* Backend development using Python
* Debugging and integrating multiple cloud services
* Strong documentation and project presentation skills

---

## Future Enhancements

* CI/CD pipeline for automated deployments
* Infrastructure as Code (Terraform or AWS CDK)
* Enhanced analytics and monitoring
* Custom domain with Route 53 (if not already implemented)

---

## 👤 Author

**Oluwatomiwa Baruwa**
Cloud Computing Student @ Morgan State University
Expected Graduation: 2027
