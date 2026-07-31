# 🤖 AI Customer Service Agent

An intelligent, fully automated backend workflow built with Make.com, integrating Google Workspace and AI Agents to handle customer requests dynamically for a bakery/restaurant system.

## 🌟 Overview
This project automates the customer service and order processing pipeline. The core of this project is a sophisticated AI-driven backend that classifies intents and routes tasks automatically. 

*Note: To simulate the restaurant's native application software and frontend data intake, a simple form and spreadsheet were used as the data ingestion layer.*

### Data Ingestion (Simulated Frontend):
Customer data (inquiries, orders, complaints) flows directly into our tracking database, triggering the automated AI workflow.
<img width="1280" height="800" alt="PHOTO-2026-07-30-06-05-25" src="https://github.com/user-attachments/assets/235fac5c-715f-4346-8cfd-a82ac914d27e" />


## 🚀 Features
- **Intelligent Intent Recognition:** Uses an AI Agent to classify customer inputs into specific categories (Questions, Orders, Complaints).
- **Automated Routing:** Dynamically directs the workflow based on the AI's data parsing and analysis.
- **Personalized Communication:** Drafts and sends context-aware emails to resolve missing order details or address complaints without human intervention.

## 🛠️ Architecture & Tech Stack (Make.com Scenario)
- **Make.com:** Orchestrates the core backend workflow.
- **Make AI Agent:** Natural language understanding and decision-making engine.
- **Google Sheets:** Acts as the database and automation trigger.
- **JSON:** Parsing structured data from the AI output.
- **Gmail:** Outbound communication layer.

### Core Backend Architecture Visualized:
blob:https://gemini.google.com/4188dfc1-b4e0-4732-ab40-bc59eda54163


## ✨ The Final Result (AI-Generated Email)
The AI intelligently analyzes the ingested data, detects discrepancies (like asking for chocolate cookies but selecting a different flavor option), and autonomously emails the customer for clarification.
blob:https://gemini.google.com/7d8432ce-3d9e-48f4-8284-ee592de3d434



## 👨‍💻 Author
**Meshal Alsalem**
