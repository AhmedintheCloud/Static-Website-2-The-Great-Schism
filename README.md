# Static-Website-2-The-Great-Schism
Host a static website using Amazon S3
#  AWS Project: Static Website Hosting on S3

## 📌 Overview
This project demonstrates how to host a static website using **Amazon S3's Static Website Hosting feature**.

## 🛠️ AWS Services Used
- **S3** (for website hosting)
- **IAM** (for permissions and bucket policy)

## 🧰 Setup Instructions
1. Create an S3 bucket (unique name).
<img width="1586" height="506" alt="Screenshot 2025-08-26 154625" src="https://github.com/user-attachments/assets/d7e88e11-b0e3-42f5-8c8a-25feb3e9c329" />

2. Upload `index.html` and other files. 
<img width="1806" height="740" alt="image" src="https://github.com/user-attachments/assets/4be0919b-2f77-4283-9400-7b7670ee2505" />


3. Enable **Static Website Hosting** in bucket properties.
<img width="1854" height="502" alt="Screenshot 2025-08-26 154902" src="https://github.com/user-attachments/assets/af52c0c0-18d0-4d9a-94f3-42a45951687b" />

4. Add a **bucket policy** to allow public read access.
<img width="878" height="514" alt="Screenshot 2025-08-26 155019" src="https://github.com/user-attachments/assets/68313515-4649-46b5-ad02-3f9b2de8a17f" />

5. Access the site using the bucket's **website endpoint**.
<img width="1377" height="935" alt="image" src="https://github.com/user-attachments/assets/2c9aa232-f815-4a10-8645-81f8596c6f86" /> 
http://starwars-static-website.s3-website-us-east-1.amazonaws.com 

The pictures displayed in this README are to demonstrate the steps taken to create the static website. I delete all resources when done to avoid unnecessary charges 


