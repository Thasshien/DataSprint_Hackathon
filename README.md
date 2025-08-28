AI-Powered HR Self-Service Assistant
Problem Statement (DSIG 3)
Develop an AI-powered self-service HR assistant that automates employee lifecycle tasks including onboarding, leave management, policy queries, and exit processes.

Why it Matters
Streamlines HR operations

Reduces SLA breaches

Improves employee satisfaction

Data Sources & APIs
HRIS/Payroll APIs (Workday, HRNet, Paylocity)

Company SSO integration

Employee policy documents and internal knowledge base

Prototype Goal
Build a conversational UI to handle common HR queries

Automate at least two workflows (e.g., leave approval, asset issuance) with static data

What We Have Done So Far
Frontend with a clean, intuitive UI for seamless employee experience.

Secure login area implemented, allowing only authorized employees to access sensitive HR data.

JWT tokens used for robust authentication and session management.

Backend operational: manages login, authentication, and API requests.

MongoDB set up as a static database for storing employee and policy data.

AI-powered HR chatbot fully integrated with the system.

Chatbot handles a wide range of queries, including working hours, remote work policies, expenses and benefits, emergency contacts, HR guidelines, IT-related questions, and exit policies.

System ensures security, efficiency, and streamlined HR operations.

Employees receive instant and accurate responses through conversational interaction.

How to Run
Install dependencies:

React (frontend)

Node.js & Express (backend)

MongoDB (database)

Ollama for LLM integration

Connect APIs:

Integrate HRIS/Payroll as needed for live data access.

Start services:

Run frontend, backend, and database individually.

Ensure Ollama service is running with the selected LLaMA model.

Login & Use:

Employees log in via secure UI

Submit HR queries and workflows through the chatbot

Next Steps
Expand API integrations for real-time data sync.

Implement additional workflows for more HR operations.

Enhance chatbot capabilities for broader topics and automation.
