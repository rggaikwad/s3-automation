
📦 Automated PNG Transfer Between S3 Buckets using AWS Lambda
This project demonstrates how to build a serverless automation system using AWS Lambda that automatically transfers .png files uploaded to a source S3 bucket (bucket1) into a subdirectory (copied-images/) of a destination bucket (bucket2). The function ignores all other file types and includes basic error handling.

🎯 Objective
Trigger a Lambda function on .png file uploads to bucket1.

Automatically copy the file to a copied-images/ folder in bucket2.

Use Python 3.12 with boto3 and IAM permissions.

✅ Prerequisites
AWS account with access to S3 and Lambda.

Basic understanding of AWS IAM, S3, and Lambda functions.

Python knowledge (basic).
