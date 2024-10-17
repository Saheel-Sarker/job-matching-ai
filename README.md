# job-matching-ai
A project to match job postings with resumes using AI and AWS services.

## Project Overview
This project is aimed at helping users find job postings that best match their resumes using AI. By leveraging AWS services and Terraform for cloud infrastructure management, we build a solution that scrapes job postings (using authorized APIs), evaluates the match against the user's resume, and recommends the best fit.

## Features
- Scrape job postings from multiple platforms using their APIs
- Use AI (AWS Comprehend/Personalize) to score job matches based on user resume
- Save job postings for later application
- REST API to interact with the system
- Infrastructure as code with Terraform for easy deployment

## Technology Stack
- **AWS Services**: Lambda, S3, API Gateway, Comprehend, Personalize
- **IaC**: Terraform
- **Backend**: Python, Flask/Express
- **Version Control**: Git, GitHub
