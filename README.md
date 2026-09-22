Instagram AI Customer Support Automation

An AI-powered customer support workflow built with n8n that processes Instagram direct messages, classifies customer intent, generates AI-assisted responses, and stores conversation data in Airtable.

📌 Project Overview

This is a self-directed AI automation project designed to demonstrate how businesses can automate repetitive Instagram customer-support tasks.

The workflow connects Instagram/Meta APIs with n8n, an AI agent, and Airtable to create an automated customer-support pipeline.

🎯 Problem

Businesses can receive large numbers of Instagram messages about:

Product questions
Shipping
Orders
Returns and refunds
Collaborations
Spam

Manually processing every message can be repetitive and time-consuming.

💡 Solution

This automation receives Instagram messages through a webhook and processes them using an n8n workflow.

The system:

Receives an Instagram DM through a webhook.
Extracts the user's message and information.
Processes the message through workflow logic.
Uses an AI Agent to understand the customer's request.
Classifies the conversation.
Generates an appropriate response.
Looks up available Instagram profile information.
Stores the conversation in Airtable.
Identifies conversations that may require human support.
⚙️ Workflow Architecture
Instagram DM
     ↓
Meta / Instagram Webhook
     ↓
Format Instagram Message
     ↓
Workflow Logic
     ↓
AI Agent
     ↓
Intent + Sentiment Analysis
     ↓
Generate Response
     ↓
Instagram Profile Lookup
     ↓
Airtable
     ↓
Conversation Record
✨ Features
Instagram DM webhook integration
AI-powered message processing
Customer intent classification
Sentiment analysis
Human-support escalation
Instagram profile lookup
Airtable conversation logging
Automated workflow routing
REST API integration
Structured conversation data
🗂️ Conversation Categories

The AI system can classify conversations into categories such as:

Product Question
Shipping
Order Issue
Return / Refund
Collaboration
Spam

It can also identify whether a conversation should be escalated to human support.

🛠️ Tech Stack
Technology	Purpose
n8n	Workflow automation
Instagram / Meta API	Instagram messaging integration
AI Agent	Message understanding and response generation
Airtable	Conversation database
Webhooks	Real-time event handling
REST APIs	System integrations
JSON	Structured data processing
🧩 Main Workflow Components
1. Instagram Webhook

Receives incoming Instagram messaging events from Meta.

2. Message Formatting

Extracts useful information such as:

User ID
Message
Timestamp
3. AI Processing

The AI Agent analyzes the incoming message and determines the appropriate category and response.

4. Profile Lookup

Instagram profile information can be retrieved through the relevant API integration.

5. Airtable Storage

Conversation information is stored in an Airtable table for tracking and support management.

📊 Example Data

Example conversation fields include:

User ID
Username
Name
Message
Timestamp
Conversation ID
Category
Sentiment
Status
Needs Human
🔐 Security

No API keys, access tokens, webhook verification tokens, passwords, or private credentials are included in this repository.

The workflow should be configured with environment-specific credentials before deployment.

📷 Screenshots

Screenshots of the n8n workflow and Airtable database will be added to this repository.

👩‍💻 About

This project was created as a self-directed portfolio project while studying BS Artificial Intelligence at The University of Lahore.

It demonstrates practical experience with:

AI automation
n8n workflows
API integrations
Webhooks
AI agents
Airtable
Instagram/Meta APIs
Workflow logic
📌 Project Status

Portfolio / Self-directed Project

The project is intended to demonstrate technical skills and workflow design. It is not presented as a paid client deployment.

📬 Contact

Dua Fatima

Email: fdua10384@gmail.com

GitHub: dua-fattimaa
