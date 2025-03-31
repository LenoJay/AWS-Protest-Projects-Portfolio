# 🚀 Real-Time Protest Tracker & Alert System (Fullstack Web App)

## Project Overview and Goals

**Project Overview:**

The Real-Time Protest Tracker & Alert System is a comprehensive web application designed to monitor and document protest activities globally. It aggregates live data, displays an interactive map with alerts, and enables users to receive real-time notifications through multiple channels, fostering informed engagement and timely responses.&#8203;:contentReference[oaicite:0]{index=0}

**Project Goals:**

- **Live Data Aggregation:** :contentReference[oaicite:1]{index=1}&#8203;:contentReference[oaicite:2]{index=2}
- **Interactive Mapping:** :contentReference[oaicite:3]{index=3}&#8203;:contentReference[oaicite:4]{index=4}
- **Real-Time Notifications:** :contentReference[oaicite:5]{index=5}&#8203;:contentReference[oaicite:6]{index=6}
- **User Interaction:** :contentReference[oaicite:7]{index=7}&#8203;:contentReference[oaicite:8]{index=8}
- **Data Analysis:** :contentReference[oaicite:9]{index=9}&#8203;:contentReference[oaicite:10]{index=10}

## Technologies and AWS Services Used

**Frontend:**

- **React.js:** :contentReference[oaicite:11]{index=11}&#8203;:contentReference[oaicite:12]{index=12}
- **Redux:** :contentReference[oaicite:13]{index=13}&#8203;:contentReference[oaicite:14]{index=14}
- **Leaflet.js:** :contentReference[oaicite:15]{index=15}&#8203;:contentReference[oaicite:16]{index=16}

**Backend:**

- **Node.js with Express:** :contentReference[oaicite:17]{index=17}&#8203;:contentReference[oaicite:18]{index=18}
- **MongoDB:** :contentReference[oaicite:19]{index=19}&#8203;:contentReference[oaicite:20]{index=20}

**AWS Services:**

- **EC2 (Elastic Compute Cloud):** :contentReference[oaicite:21]{index=21}&#8203;:contentReference[oaicite:22]{index=22}
- **Lambda:** :contentReference[oaicite:23]{index=23}&#8203;:contentReference[oaicite:24]{index=24}
- **API Gateway:** :contentReference[oaicite:25]{index=25}&#8203;:contentReference[oaicite:26]{index=26}
- **S3 (Simple Storage Service):** :contentReference[oaicite:27]{index=27}&#8203;:contentReference[oaicite:28]{index=28}
- **DynamoDB:** :contentReference[oaicite:29]{index=29}&#8203;:contentReference[oaicite:30]{index=30}
- **CloudFront:** :contentReference[oaicite:31]{index=31}&#8203;:contentReference[oaicite:32]{index=32}
- **Route 53:** :contentReference[oaicite:33]{index=33}&#8203;:contentReference[oaicite:34]{index=34}
- **EventBridge:** :contentReference[oaicite:35]{index=35}&#8203;:contentReference[oaicite:36]{index=36}
- **SNS (Simple Notification Service):** :contentReference[oaicite:37]{index=37}&#8203;:contentReference[oaicite:38]{index=38}
- **Cognito:** :contentReference[oaicite:39]{index=39}&#8203;:contentReference[oaicite:40]{index=40}
- **Lex:** :contentReference[oaicite:41]{index=41}&#8203;:contentReference[oaicite:42]{index=42}
- **CloudWatch:** :contentReference[oaicite:43]{index=43}&#8203;:contentReference[oaicite:44]{index=44}

## Step-by-Step Implementation Instructions

1. **Frontend Development:**
   - **Set Up React Application:**
     - Initialize a new React project using Create React App.
     - Develop components for the homepage, protest listings, detailed views, and user dashboards.
   - **State Management:**
     - Implement Redux to handle global state, such as user authentication status and protest data.
   - **Map Integration:**
     - Integrate Leaflet.js to display interactive maps with real-time protest locations and details.

2. **Backend Development:**
   - **Set Up Server:**
     - Create an Express server to handle API routes and client requests.
   - **Database Integration:**
     - Connect the server to MongoDB using Mongoose for data modeling.
     - Design schemas for protests, users, and analytics data.
   - **API Development:**
     - Develop RESTful APIs to fetch, add, update, and delete protest records.
     - Implement authentication endpoints using JWT (JSON Web Tokens).

3. **AWS Integration:**
   - **EC2 Deployment:**
     - Launch an EC2 instance to host the backend server.
     - Configure security groups and key pairs for secure access.
   - **Lambda Functions:**
     - Create Lambda functions to process incoming protest data, such as analyzing social media feeds.
   - **API Gateway:**
     - Set up API Gateway to expose RESTful endpoints for data ingestion and user interactions.
   - **S3 Storage:**
     - Set up S3 buckets to store media files associated with protests.
   - **DynamoDB:**
     - Design tables to store real-time protest event data for low-latency access.
   - **CloudFront:**
     - Configure CloudFront to deliver content globally with low latency and high transfer speeds.
   - **Route 53:**
     - Set up Route 53 to manage domain names and DNS routing for the application.
   - **EventBridge:**
     - Use EventBridge to orchestrate event-driven updates, such as triggering notifications for new protests.
   - **SNS:**
     - Configure SNS to send notifications (SMS/email) to users upon detection of new protests.
   - **Cognito:**
     - Implement Cognito for user sign-up, sign-in, and access control mechanisms.
   - **Lex:**
     - Develop a conversational chatbot using Lex to handle protest-related queries.
   - **CloudWatch:**
     - Set up CloudWatch to monitor system performance and log real-time events.

## Screenshots and Diagrams

**Interactive Map of Protests:**

![Interactive Map](assets/images/interactive_map.png)

*Figure 1: Interactive map displaying real-time protest locations and details.*

**AWS Architecture Diagram:**

![AWS Architecture](assets/images/aws_architecture.png)

*Figure 2: AWS architecture diagram illustrating the integration of various AWS services used in the application.*

*
::contentReference[oaicite:45]{index=45}
