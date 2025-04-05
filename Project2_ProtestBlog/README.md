# Dynamic Protest Blog with User Submissions

## Project Overview and Goals

**Overview:**  
This project is a dynamic web application that serves as a blog for protest-related content. Users can submit posts, upload media files, and comment on articles. The platform incorporates AI-powered content moderation to ensure a safe community space.

**Goals:**
- Allow users to submit and interact with protest-related posts.
- Use AI to moderate media content (images/videos) for compliance.
- Provide a seamless and scalable deployment using managed AWS services.
- Ensure data integrity and high-performance database interactions.

## Technologies and AWS Services Used

**Frontend:**
- **React.js & Redux:** For building a dynamic, interactive user interface.
- **Bootstrap/Material-UI:** For responsive design.

**Backend:**
- **Elastic Beanstalk:** Simplifies deployment and scaling of the application.
- **Aurora (RDS engine):** High-performance relational database for storing posts, comments, and user data.
- **EFS:** Stores large media files (images, videos).
- **API Gateway + Lambda:** Processes user submissions and validates content.
- **S3:** Archives static content and backups.
- **Cognito:** Manages user authentication and profiles.
- **CloudFront:** Accelerates global content delivery.
- **CloudTrail:** Audits API calls and user actions.
- **Rekognition:** Moderates uploaded media for inappropriate content.
- **AWS Step Functions:** Orchestrates multi-step workflows for submission and moderation.

## Step-by-Step Implementation Instructions

1. **Frontend Setup:**
   - Initialize your React project and build components for blog listings, post creation, and commenting.
   - Integrate Redux for state management.
   - Style the application with Bootstrap or Material-UI.

2. **Backend and Database:**
   - Deploy the application using Elastic Beanstalk.
   - Set up Aurora as your relational database and design your schema for posts, comments, and user data.
   - Configure EFS for handling media uploads.
   - Develop APIs with API Gateway and Lambda to handle post submissions and moderation.

3. **Content Moderation & Deployment:**
   - Integrate Rekognition to scan uploaded images/videos for inappropriate content.
   - Use AWS Step Functions to coordinate the multi-step process of content submission and moderation.
   - Configure CloudFront for efficient global content delivery and CloudTrail for auditing.

## Screenshots and Diagrams

- **Blog Interface:**  
  *Placeholder: Insert a screenshot of the blog homepage and post submission form.*

- **Architecture Diagram:**  
  *Placeholder: Include a diagram showing Elastic Beanstalk, Aurora, EFS, and Lambda integration.*

## Additional Information

- Focus on ensuring data consistency and security for user-generated content.
- Document any performance optimizations and security measures implemented.

