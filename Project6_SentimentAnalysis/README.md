# Protest Sentiment Analysis & Insights

## Project Overview and Goals

**Overview:**  
This project focuses on analyzing textual data from social media, news outlets, and blogs to gauge public sentiment regarding protests. It provides insights through interactive dashboards, helping stakeholders understand public opinion and media coverage trends.

**Goals:**
- Analyze protest-related texts to determine sentiment (positive, negative, neutral).
- Visualize sentiment trends over time in an interactive dashboard.
- Provide endpoints for retrieving sentiment analysis results.
- Operate as a batch or periodic analysis rather than strictly real-time.

## Technologies and AWS Services Used

**Analytics & NLP:**
- **Amazon Comprehend:** Performs NLP-based sentiment analysis.
- **Amazon Kinesis:** Streams textual data (used in batch mode for periodic analysis).
- **AWS Lambda:** Processes and integrates sentiment data.
- **S3:** Archives raw and processed sentiment datasets.
- **DynamoDB:** Stores structured sentiment insights.
- **Amazon QuickSight:** Visualizes sentiment trends in interactive dashboards.
- **API Gateway:** Exposes endpoints for data retrieval.
- **EventBridge:** Automates workflow triggers based on sentiment changes.
- **CloudWatch:** Monitors processing and performance.

## Step-by-Step Implementation Instructions

1. **Data Collection and Ingestion:**
   - Set up Kinesis to ingest textual data from social media and news sources in periodic batches.
   - Store incoming data in S3 for processing.

2. **Sentiment Analysis:**
   - Use Lambda functions to trigger sentiment analysis with Amazon Comprehend.
   - Store processed sentiment data in DynamoDB.

3. **Visualization and Reporting:**
   - Create interactive dashboards with QuickSight to display sentiment trends.
   - Set up API Gateway endpoints to allow external access to sentiment data.
   - Use EventBridge to schedule periodic sentiment analysis workflows.

4. **Monitoring:**
   - Configure CloudWatch to monitor Lambda execution, data ingestion, and dashboard performance.

## Screenshots and Diagrams

- **Dashboard Screenshot:**  
  *Placeholder: Insert a screenshot of the sentiment analysis dashboard.*
- **Workflow Diagram:**  
  *Placeholder: Insert a diagram illustrating the sentiment analysis pipeline.*

## Additional Information

- Focus on batch processing rather than continuous real-time analysis.
- Document the sentiment analysis methodology and any threshold settings used for triggering alerts.

