This project involves building a functional AI customer support agent with Amazon Bedrock AgentCore, AWS Lambda, RAG and strandsSDK. This AI customer support agent can answer questions about products, return policies and loyalty rewards using Retrieval-Augmented Generation (RAG), look up order status and process refunds by calling Lambda functions through the AgentCore Gateway, remember customer preferences and conversation history across multiple sessions, calculate exact loyalty discounts using a secure code sandbox and navigate websites to fetch live information.

Prerequisites
AWS Account
An active AWS account with permission to create and manage:
IAM roles and policies
Lambda functions
API Gateway REST APIs
Amazon Bedrock Managed Knowledge Bases (with S3 access)
Amazon Bedrock AgentCore resources (Runtime, Gateway, Memory)

project/
└── starter/
    ├── main.py                  ← your starting point (fill in the TODOs)
    ├── setup_permissions.py     ← run after deployment to configure the agent role
    ├── pyproject.toml           ← Python dependencies
    ├── product_catalog.txt      ← upload to the Knowledge Base
    └── lambda/
        ├── order_tracker.py     ← deploy as-is
        ├── refund_processor.py  ← deploy as-is
        └── lambda_schema        ← refund tool schema

 

