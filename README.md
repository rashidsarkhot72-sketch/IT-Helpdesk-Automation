# 🛠️ IT Helpdesk Ticket Automation System

An AWS-based IT Helpdesk system that allows employees to create support tickets and track their ticket status. Admins can manage tickets and update their status and remarks.

## 🚀 Features

- Employee ticket submission
- Ticket ID generation
- Track ticket status
- Admin login
- Admin dashboard
- Update ticket status
- Add admin remarks
- Email notification for new tickets
- Automated ticket processing using SQS

## ☁️ AWS Services Used

- **Amazon API Gateway** – REST API for the application
- **AWS Lambda** – Backend ticket processing
- **Amazon DynamoDB** – Stores helpdesk tickets
- **Amazon SQS** – Handles asynchronous ticket processing
- **Amazon SNS** – Sends email notifications
- **Amazon CloudWatch** – Logs and monitoring
- **AWS IAM** – Access permissions

## 🔄 Architecture

Employee
↓
API Gateway
↓
Lambda
↓
DynamoDB
↓
SQS
↓
Worker Lambda
↓
SNS
↓
Email Notification

## 📂 Project Structure

```text
IT-Helpdesk-Automation/
└── frontend/
    ├── index.html
    ├── login.html
    ├── admin.html
    └── track.html
🎯 Ticket Status
Pending
In Progress
Resolved
🔐 Admin Login

This project currently uses a simple frontend demo login for the admin dashboard.

Note: The demo login is for project demonstration purposes and is not production-grade authentication.

👨‍💻 Author

Rashid Sarkhot
