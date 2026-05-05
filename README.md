# 🔐 AWS IAM + S3 + KMS Security Project

Designed and implemented a secure AWS storage environment using IAM, S3, and KMS to enforce encryption at rest and least privilege access control.

---

## 🏗️ Architecture Overview
- IAM users and roles with least privilege access
- S3 bucket secured with server-side encryption (SSE-KMS)
- Customer-managed KMS key for encryption control
- Bucket tagging for access organization (ABAC-ready)

---

## 🛠️ Security Features Implemented
- Created IAM users and assigned controlled permissions
- Configured a customer-managed KMS key
- Enabled SSE-KMS encryption on S3 bucket
- Applied bucket-level encryption policies
- Controlled access to encryption keys via IAM

---

## 🔑 KMS Key Created
![KMS Key](screenshots/kms-key.png)

## ⚙️ KMS Configuration
<img src="https://github.com/user-attachments/assets/c1c69d62-81a9-4197-b405-257dad0eafa8" width="900" />

## 🔐 S3 Encryption Enabled
<img src="https://github.com/user-attachments/assets/3e684996-5ba6-4cb2-9c6d-a787e6833bb6" width="900" />

## 📦 S3 Object Upload
<img src="https://github.com/user-attachments/assets/173cbefb-8e79-4438-b0c6-f4ebb3fbca02"  width="900" />

---

## 🎯 Outcome
Built a secure AWS storage solution demonstrating real-world cloud security practices:
- Data encryption at rest using KMS
- Identity-based access control (IAM)
- Secure key management and access policies

---

## 🧠 What I Learned
- Difference between SSE-S3 and SSE-KMS
- How IAM controls access to encrypted resources
- Importance of least privilege access
- How KMS integrates with S3 for secure storage

---

## ⚠️ Security Considerations
- Restricted KMS key access to specific IAM users only
- Ensured all S3 objects are encrypted
- Prevented unauthorized access using IAM policies
- Centralized encryption key management with KMS

---

## 🧰 Skills Demonstrated
- AWS IAM
- Amazon S3 Security
- AWS KMS
- Encryption (SSE-KMS)
- Access Control (RBAC / ABAC basics)
