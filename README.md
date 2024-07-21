# AWS Lambda Integration with Bedrock for Automated Content Generation
This repository contains AWS Lambda functions designed to automate content generation tasks using Bedrock models. The functions can generate Python code, images from textual prompts, and meeting summaries. The generated content is then saved to an AWS S3 bucket for easy access and management.
Features

![1693422997516](https://github.com/user-attachments/assets/9b517442-787e-4a62-b02f-64614e35c354)


    Code Generation: Generates Python code based on provided instructions using Bedrock models.
    Image Generation: Creates images from textual descriptions using Bedrock's Stable Diffusion model.
    Meeting Summarization: Extracts text from multipart email data and generates concise summaries using Bedrock models.
    AWS Integration: Utilizes boto3 to interact with AWS Lambda, S3, and Bedrock for seamless content generation and storage.
