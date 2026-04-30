## Architecture Diagram

![image alt](https://github.com/teajo99/aws-iam-s3-access-control-project/blob/453df7516e525e62f8eb88c4109db3ea5ec5d6d4/aws-iam-s3-access-control-project/screenshot%20folder/architecture%20diagram/IAM%20AND%20S3.png)

# 🏥 Secure Hospital Data Platform (AWS IAM + S3)

## 📌 Project Summary

This project demonstrates how a hospital can securely store and control access to sensitive patient data using AWS cloud services.

It simulates a real-world healthcare environment where only authorised medical staff can access patient records, while other departments are restricted.

The focus is on **data security, access control, and compliance-ready architecture**.

---

## 🎯 Business Problem

Hospitals manage large volumes of sensitive data such as:

- Patient reports  
- X-rays and scans  
- Lab results  

Key challenges:
- Prevent unauthorised access to medical data  
- Ensure role-based access for different staff  
- Maintain compliance with data protection standards  
- Store large datasets securely and cost-effectively  

---

## 💡 Proposed Solution

This project uses AWS services to solve these challenges:

- **Amazon S3** → Secure storage for patient records  
- **AWS IAM** → Role-based access control for hospital staff  

---

## 🏗️ Architecture Overview

- S3 bucket stores all patient data securely  
- IAM users represent hospital staff roles  
- IAM policies control who can access the data  
- Access is granted based on job function (least privilege principle)  

---

## ☁️ AWS Services Used

- Amazon S3  
- AWS Identity and Access Management (IAM)

---

## 👥 User Roles

### 👨‍⚕️ Doctor
- Full read access to patient records
- Can access S3 bucket securely

### 👨‍💼 Accountant
- No access to patient medical data
- Access is restricted by IAM policies

---

## 🔐 Security Design

- Block public access enabled on S3 bucket  
- IAM enforces least privilege access  
- Only authorised users can access sensitive data  
- All access attempts are controlled through IAM policies  

---

## 🚀 Implementation Summary

- Created S3 bucket for hospital data storage  
- Uploaded sample patient files (reports, scans, lab results)  
- Created IAM users representing hospital staff  
- Assigned permissions based on roles  
- Tested access control for allowed vs restricted users  

---

## 📊 Key Results

✔ Doctors successfully accessed patient records  
❌ Accountants were denied access to medical data  
✔ Data remained private and secure at all times  

---

## 🧠 Key Learning Outcomes

- Understanding IAM role-based access control  
- Secure cloud storage using S3  
- Implementation of least privilege principle  
- Real-world healthcare security design in AWS  

---

## 🌍 Real-World Relevance

This architecture reflects how real hospitals:
- Protect patient confidentiality  
- Enforce strict access control policies  
- Use cloud storage for scalable medical data management  
- Maintain compliance with healthcare regulations (e.g. HIPAA principles)

---

## 📸 Screenshots

Include:
- S3 bucket creation  
- Uploaded medical files  
- IAM user setup  
- Access granted vs denied results  

---

## 📌 Future Improvements

- Add VPC isolation for network-level security  
- Introduce encryption for S3 data  
- Implement logging with CloudTrail  
- Expand to multi-department hospital system  

---

## 🔗 Author

AWS Cloud Learning Project by Temitope Ajo  
Focused on building real-world cloud architecture skills through hands-on projects.
