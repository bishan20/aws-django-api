# AWS Django API Deployment

## Overview
This project demonstrates deploying a simple **Django REST API** on **Amazon Web Services (AWS)** using **AWS Elastic Beanstalk**.  
It was built to gain hands-on experience with cloud computing concepts such as application deployment, virtualized infrastructure, security configuration, and cost awareness using AWS Free Tier services.

The application exposes a basic API endpoint to confirm that the service is running successfully in a cloud environment.

---

## Tech Stack
- **Language:** Python
- **Framework:** Django, Django REST Framework
- **Cloud Provider:** Amazon Web Services (AWS)
- **Deployment Service:** AWS Elastic Beanstalk
- **Compute:** Amazon EC2 (Elastic Beanstalk–managed)
- **Storage:** Amazon S3
- **Testing:** Postman

---

## Deployment Process

1. Created an AWS account using the Free Tier.
2. Initialized an Elastic Beanstalk Python environment.
3. Configured dependencies using requirements.txt and application startup using Procfile.
4. Deployed the Django REST API to AWS Elastic Beanstalk.
5. Verified deployment using the public Elastic Beanstalk URL.
6. Tested API endpoints using Postman.

---

## API Functionality
The API provides a simple health check endpoint:

`GET /api/health/`

**Response:**
```json
{
  "message": "API is working!"
}

