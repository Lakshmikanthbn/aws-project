# Serverless Web Application: Feedback Submission and Viewing

## Objective
Build a simple web application that allows users to submit and view feedback. The application will be fully serverless, leveraging AWS services to handle the backend logic, data storage, and frontend hosting.

## AWS Services Used
- **AWS Lambda**: For backend logic.
- **Amazon API Gateway**: For creating APIs.
- **Amazon DynamoDB**: For storing feedback data.
- **Amazon S3**: For hosting the static web application.
- **AWS IAM**: For managing access permissions.
- **AWS CloudFormation** (optional): For infrastructure as code.

## Project Structure

### Frontend
- **HTML/CSS/JavaScript**: Create a simple frontend.
- **Amazon S3**: Host the frontend.

### Backend
- **Amazon API Gateway**: Create a RESTful API.
- **AWS Lambda**: Implement backend logic.
- **Amazon DynamoDB**: Store feedback data.

## Getting Started

### Prerequisites
- AWS Account
- AWS CLI configured with proper access
- Basic knowledge of AWS services and web development

### Setup Instructions

#### 1. Frontend
1. Create your HTML/CSS/JavaScript files for the frontend.
2. Create an S3 bucket and upload your frontend files:
   ```sh
   aws s3 mb s3://your-bucket-name
   aws s3 cp . s3://your-bucket-name/ --recursive
