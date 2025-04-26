# AWS Project: Hosting a Static/Dynamic Website on AWS Amplify (Free Tier)

## Overview
This project demonstrates how to host a dynamic website using AWS services while leveraging the free tier. The architecture is designed for security, cost efficiency, and scalability.

---
![AWS Architecture](https://github.com/user-attachments/assets/99e2b5cd-7e1e-4a5c-b0b1-074959a82ddb)


## Key AWS Services Used

### 1. **Amazon S3**
- **Purpose**: Acts as the storage location for website files (HTML, CSS, JavaScript, and other assets).
- **Implementation**: Website files are uploaded to an Amazon S3 bucket, ensuring secure and scalable storage.

### 2. **AWS Amplify**
- **Purpose**: Provides streamlined hosting and management for the dynamic website.
- **Implementation**: The S3 bucket is linked to AWS Amplify for seamless deployment and hosting.

### 3. **AWS Identity and Access Management (IAM)**
- **Purpose**: Enhances security by restricting access to AWS resources.
- **Implementation**: A dedicated IAM user, `abc`, was created with permissions limited to Amazon S3 and AWS Amplify services.

### 4. **AWS Budgets**
- **Purpose**: Monitors costs to ensure adherence to the Free Tier.
- **Implementation**: A budget of $1 is set up. Alerts are configured to notify if costs exceed this limit.

---

## Workflow

1. **Upload Website Files**  
   Website files are uploaded to an Amazon S3 bucket.

2. **Connect S3 to Amplify**  
   The S3 bucket is linked to AWS Amplify, enabling smooth hosting.

3. **Security Configuration**  
   IAM user `abc` is created with permissions restricted to S3 and Amplify services only.

4. **Cost Monitoring**  
   AWS Budgets is configured to raise alerts if costs exceed $1, ensuring free-tier adherence.

---

## Benefits

- **Secure Architecture**: Leveraging IAM ensures resources are accessed only by authorized users.
- **Cost Management**: AWS Budgets prevent unexpected billing issues.
- **Scalability**: Amazon S3 and AWS Amplify provide seamless scalability for hosting.

---

## Future Scope

- Explore additional AWS services for analytics and monitoring.
- Optimize hosting performance using CloudFront and Route 53.

---

