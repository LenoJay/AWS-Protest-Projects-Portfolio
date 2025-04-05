# Secure Data Sharing Platform for Whistleblowers

## Project Overview and Goals

**Overview:**  
This platform is designed to facilitate the secure exchange of sensitive protest-related documents among whistleblowers and human rights organizations. Emphasizing data security and compliance, the system ensures that confidential information is stored, classified, and accessed only by authorized users.

**Goals:**
- Provide secure, encrypted storage for sensitive documents.
- Enable controlled, role-based access to shared files.
- Implement intelligent data classification and search.
- Protect public-facing endpoints against DDoS and web attacks.

## Technologies and AWS Services Used

**Security & Compliance:**
- **S3 (encrypted):** Secure storage with encryption at rest.
- **KMS:** Encrypts data to maintain confidentiality.
- **Secrets Manager:** Protects API keys and sensitive credentials.
- **AWS Shield + WAF:** Provides DDoS and web attack protection.
- **Amazon Macie:** Automatically discovers and classifies sensitive data.

**Application & Networking:**
- **API Gateway + Lambda:** Handles secure file uploads/downloads.
- **CloudFront:** Distributes content securely with low latency.
- **Cognito:** Manages user authentication and role-based access.
- **Amazon VPC:** Ensures network isolation for sensitive components.

## Step-by-Step Implementation Instructions

1. **Security Setup:**
   - Create an S3 bucket with encryption enabled and configure KMS keys.
   - Set up IAM roles and policies to enforce least privilege.
   - Enable Amazon Macie to scan and classify sensitive data in your S3 bucket.
   - Configure AWS Shield and WAF to protect your API endpoints and CloudFront distribution.

2. **Application Deployment:**
   - Develop Lambda functions to handle file uploads/downloads via API Gateway.
   - Set up CloudFront for secure and efficient content delivery.
   - Configure Cognito for user sign-up and access control.

3. **Networking:**
   - Create a dedicated VPC to host critical components, ensuring isolation and enhanced security.
   - Configure security groups to control traffic flow.

## Screenshots and Diagrams

- **Secure Architecture Diagram:**  
  *Placeholder: Insert a diagram showing the secure data sharing flow including S3, Lambda, VPC, Shield+WAF, and Macie.*

- **User Interface Screenshot:**  
  *Placeholder: Insert a screenshot of the secure file upload and access portal.*

## Additional Information

- Emphasize compliance with data protection standards.
- Document the IAM and security policies used to safeguard sensitive data.

