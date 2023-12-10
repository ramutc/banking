# Objective:

 The primary objective of this project is to design, develop, and deploy an end-to-end serverless banking system on AWS that offers secure, scalable, and efficient financial services to users. The system aims to provide essential banking functionalities such as user registration, account management, and transaction processing while leveraging AWS serverless services to ensure high availability, cost-effectiveness, and adherence to security best practices. Additionally, the project aims to showcase the integration of various AWS services in a cohesive architecture that emphasizes robustness, scalability, and optimal performance, thus serving as a demonstrative model for implementing serverless solutions in the banking sector.
# 2. Architecture Overview
•	 **Diagram**: High-level architecture diagram showcasing components and their interactions.

![image](https://github.com/ramutc/banking/assets/151390614/31663873-b89c-48c4-b79d-cb0df6dfd019)


**Components**:
   •	Amazon API Gateway
   •	AWS Lambda Functions
   •	Amazon S3 for Static Assets.


   # Data Flow Diagram for Serverless Banking System
1. **User Registration and Authentication**
•	**Client Request**: User initiates the registration process through the client application.
•	**API Gateway**: Receives the registration request.
•	**Lambda Function**: Validates user data and interacts with Cognito for user creation/authentication.
•	**Response**: Successful registration grants the user access to the banking system.

2. **Check Account Balance in our respective account**.
•	**Client Request**: Users request an account balance.
•	**API Gateway**: Routes the balancecheck request.
•	**Lambda Function**: Fetch a user details from S3 bucket and displays a Account Balance of the User.

3. **Client Interaction**
•	**Client Application**: Interfaces with the backend through API Gateway endpoints.
•	**Static Assets**: Hosted on Amazon S3 for serving client-side files (web pages, images, etc.).

**Conclusion**
This data flow diagram outlines the sequence of interactions between different components in the Serverless Banking System on AWS, detailing how user requests are processed, accounts managed, transactions executed, and security measures implemented within the serverless architecture.

**AWS Services Used:**

	Amazon API Gateway
	AWS Lambda Functions
	Amazon S3 for Static Assets
	AWS Cloudformaton for Stack Creation.


**Cloudformation Stack Template Diagram:**


![image](https://github.com/ramutc/banking/assets/151390614/0ef069f0-44db-4479-a85b-46e949af114f)



