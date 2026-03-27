🚀 Automated Receipt Processing System (AWS Serverless)

An end-to-end serverless pipeline that automatically processes receipt PDFs uploaded to an S3 bucket, extracts key information, and sends structured data via email — eliminating manual effort and improving efficiency.

📌 Overview

This project automates the process of handling receipts by:

Uploading receipt PDFs to an S3 bucket
Triggering AWS Lambda for processing
Extracting key details (amount, vendor, date)
Sending extracted data directly to your email

💡 Built to solve real-world problems in expense tracking and workflow automation.

<img width="884" height="291" alt="image" src="https://github.com/user-attachments/assets/5de36e75-07f0-4649-9515-a6090ae69d08" />


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

https://github.com/user-attachments/assets/e3965942-f226-435a-85ea-a9ca2a06399d

📊 Impact
Reduced manual effort by ~80%
Improved accuracy in expense tracking
Built a real-world automation pipeline using AWS
🚀 Future Improvements
Add OCR for scanned receipts (Textract)
Build dashboard for analytics
Store data in DynamoDB for querying
Integrate AI for smarter extraction
🧠 Learnings
Hands-on experience with AWS serverless architecture
Event-driven system design
Real-world automation use case
Cloud-based workflow optimization
🤝 Connect With Me

If you found this project interesting or want to collaborate:

LinkedIn: www.linkedin.com/in/manish-kudtarkar
GitHub: https://github.com/ManishKudtarkar
⭐ Support

If you like this project, consider giving it a ⭐ on GitHub!
