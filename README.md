# AI Data Cleaning Agent
An LLM-powered interactive system that automates data cleaning tasks using natural language instructions.
Built with LangChain + OpenAI + Pandas, this project simulates a lightweight AI data processing assistant.

Demo
Users can interact with the system using natural language:
"fill missing values using median"
"drop rows with null values"
"generate dataset summary"
The system automatically routes the request to the correct data processing module and applies transformations to the dataset.

Architecture
User Input (Natural Language)
        ↓
LangChain Router (LLM-based decision)
        ↓
Feature Selection Module
        ↓
Pandas Processing Functions
        ↓
Updated Dataset Output
