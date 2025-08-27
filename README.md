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

5. Access the site using the bucket's **website endpoint** to check functionality 
<img width="1377" height="935" alt="image" src="https://github.com/user-attachments/assets/2c9aa232-f815-4a10-8645-81f8596c6f86" /> 

6. Set up a Cloud Front CDN for improved latency, security and caching 
- make sure to enable OAC (origin access controll) and update the s3 bucket with the generated policy after creating your distribution 
<img width="1158" height="548" alt="Screenshot 2025-08-27 163920" src="https://github.com/user-attachments/assets/de423203-bda2-4777-9810-3a7119ed1159" /> 

7. Once your distribution has been successfully made, you can use your cloud front's endpoint (example:eewewdf45t54.cloudfront.net) to access your website
8. create your own domain set up with SSL certificates through route 53 and ACM (AWS Certificate Manager)



The pictures displayed in this README are to demonstrate the steps taken to create the static website. I delete all resources when done to avoid unnecessary charges 


