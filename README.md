# 🚀 Serverless Calculation Solution 🌐

This project demonstrates a **Python-based serverless solution** deployed on AWS Lambda, providing an efficient and scalable way to perform mathematical calculations via a RESTful API. It leverages AWS's robust ecosystem, including API Gateway, DynamoDB, and IAM for secure, seamless operations.

## 📜 Project Overview

This solution handles calculations as a serverless service, ensuring zero infrastructure maintenance while providing quick and scalable results. With **AWS Lambda** running the core logic and **API Gateway** exposing the function as a RESTful API, this project offers a secure and reliable way to handle calculations via the cloud.

### ✨ Features
- **Python-based Calculation Engine**: Implemented on AWS Lambda to handle requests dynamically.
- **RESTful API**: Exposed via AWS API Gateway for seamless communication with the calculation function.
- **Data Persistence**: Stores input/output data in AWS DynamoDB for future reference and logging.
- **Secure and Scalable**: Managed through AWS IAM policies, ensuring secure and controlled access.

## 🛠️ Technology Stack
- **AWS Lambda**: Serverless function for performing Python-based calculations.
- **AWS API Gateway**: To expose the calculation service as a REST API.
- **AWS DynamoDB**: NoSQL database for storing the inputs and results of calculations.
- **AWS IAM**: Configured for fine-grained permissions to secure the infrastructure.
- **Python**: The core language for writing the calculation logic.

## 🧑‍💻 Setup & Deployment

Follow these steps to deploy the Serverless Calculation Solution on your own AWS account:

### 1. Clone the Repository
```bash
git clone https://github.com/yourusername/serverless-calculation-solution.git
cd serverless-calculation-solution
