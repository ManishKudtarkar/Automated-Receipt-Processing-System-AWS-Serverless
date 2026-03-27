🚀 Automated Receipt Processing System (AWS Serverless)

An end-to-end serverless pipeline that automatically processes receipt PDFs uploaded to an S3 bucket, extracts key information, and sends structured data via email — eliminating manual effort and improving efficiency.

📌 Overview

This project automates the process of handling receipts by:

Uploading receipt PDFs to an S3 bucket
Triggering AWS Lambda for processing
Extracting key details (amount, vendor, date)
Sending extracted data directly to your email

💡 Built to solve real-world problems in expense tracking and workflow automation.

🏗️ Architecture
S3 Bucket (Upload Receipt PDF)
        ↓
AWS Lambda (Triggered)
        ↓
Data Extraction (Python Logic)
        ↓
Processed Data(Dynamo DB)
        ↓
Email Notification (SES)

⚙️ Tech Stack
AWS S3 – Storage for receipt PDFs
AWS Lambda – Serverless compute for processing
Amazon SES – Email sending service
Python – Data extraction logic
Boto3 – AWS SDK for Python

🔥 Features

✔️ Automated receipt processing
✔️ Event-driven serverless architecture
✔️ Real-time email notifications
✔️ Scalable and cost-efficient
✔️ Eliminates manual data entry

📥 Workflow
Upload receipt PDF to S3 bucket
Lambda function is triggered automatically
Python script extracts:
Amount
Vendor
Date
Processed data is formatted
Email sent via SES with extracted details

📸 Demo
