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

Features
1. Intelligent Query Routing
Uses an LLM to classify user requests and route them to the correct function.

2. Missing Value Handling
Supports multiple strategies:
Mean / Median / Mode imputation
Forward fill / Backward fill
Row removal

3. Dataset Summarization
Generates automatic dataset insights and statistics.

4. Modular Design
Each feature is implemented as an independent module (notebook-based for experimentation).
