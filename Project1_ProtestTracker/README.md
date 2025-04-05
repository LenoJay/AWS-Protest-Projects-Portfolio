# Real-Time Protest Tracker & Alert System

## Project Overview and Goals

**Overview:**  
This project is a dynamic full-stack web application that provides real-time alerts about ongoing protests. It features an interactive map where users can view live protest events and receive notifications via SMS/email. The system is designed to be scalable and responsive, ensuring timely delivery of information to users.

**Goals:**
- Aggregate live protest data from various sources.
- Display an interactive map with real-time protest event updates.
- Send instant notifications to users via multiple channels.
- Ensure secure user authentication.

## Technologies and AWS Services Used

**Frontend:**
- **React.js:** For building a responsive UI.
- **Redux:** For managing application state.
- **Amazon Amplify:** For accelerated front-end development and deployment.

**Backend:**
- **EC2 (with Auto Scaling & ELB/ALB):** Hosts dynamic web pages and APIs.
- **API Gateway:** Exposes RESTful endpoints.
- **Lambda:** Processes real-time protest data.
- **DynamoDB:** Stores protest event data.
- **SNS:** Delivers notifications.
- **Cognito:** Manages user authentication.
- **CloudWatch:** Monitors performance and logs events.

**Networking:**
- **CloudFront:** Global content delivery.
- **Route 53:** DNS and domain management.

## Step-by-Step Implementation Instructions

1. **Frontend Setup:**
   - Initialize a React project using Create React App.
   - Develop components for the interactive map, notification center, and user authentication.
   - Use Amplify to connect your front end with AWS backend services and deploy your site.

2. **Backend Setup:**
   - Launch an EC2 instance and configure it with Auto Scaling and an ELB/ALB.
   - Develop your API using Node.js/Express and deploy it on EC2.
   - Create Lambda functions for processing data feeds.
   - Set up DynamoDB tables to store protest event data.
   - Configure API Gateway to route requests to your Lambda functions.

3. **Notifications and Monitoring:**
   - Configure SNS to send notifications based on triggers from Lambda.
   - Set up Cognito for secure user sign-up and sign-in.
   - Use CloudWatch for monitoring logs and setting up alarms.
   - Configure Route 53 and CloudFront to manage DNS and deliver content globally.

## Screenshots and Diagrams

- **Interactive Map:**  
  *Placeholder: Insert a screenshot of the interactive protest map here.*

- **AWS Architecture Diagram:**  
  *Placeholder: Insert your architecture diagram illustrating EC2, API Gateway, Lambda, SNS, etc.*

## Additional Information

- Ensure you adhere to security best practices (least privilege with IAM, secure API endpoints, etc.).
- Document any challenges and how you solved them for future reference.
