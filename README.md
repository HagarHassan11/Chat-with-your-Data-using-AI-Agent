# Chat-with-your-Data-using-AI-Agent
An advanced, conversational AI-powered API that translates natural language questions into precise SQL queries, interacts with a database, and provides human-readable answers. This project goes beyond basic NL-to-SQL by implementing a multi-step, self-correcting workflow for higher accuracy and a better user experience.

## 📈 Project Workflow

This project uses a sophisticated, multi-agent chain of thought to process a user's request. This ensures a high degree of accuracy and robustness.

![image](https://github.com/user-attachments/assets/7b4272a6-e752-4249-ac8e-e947ecbf3634)

## ✨ Key Features

- 🧠 **Intelligent Query Rewriting**: Before generating SQL, an LLM refines and clarifies the user's query to make it unambiguous and aligned with the database schema.
- 🗣️ **Conversational Context**: The chatbot remembers recent messages to understand follow-up questions and maintain context.
- 🤔 **Self-Correction & Clarification Loop**: If a query yields no results, the system doesn't just fail. It intelligently asks the user for clarification, suggesting broader search strategies (e.g., changing an exact match to a 'contains' search).
- ⚙️ **Robust SQL Generation**: A dedicated LLM, armed with detailed instructions and the database schema, constructs complex SQL queries with accurate JOINs, GROUP BY clauses, and filtering logic.
- 🚀 **Built with Modern Tools**: Leverages the speed of FastAPI, the power of LangChain for LLM orchestration, and Azure OpenAI for state-of-the-art language models.
- 🔌 **Pluggable & Ready-to-Deploy**: Packaged as a clean FastAPI application, ready to be containerized and deployed.




