# Langchain-AI-Driven-Customer-Support
The Langchain project is designed to revolutionize customer support by utilizing Large Language Models (LLMs). The core objective is to develop a customer support application that delivers intelligent, context-aware responses, significantly improving the efficiency and effectiveness of customer interactions.

# Objective
To create an advanced customer support system using LLMs, enhancing user experience through intelligent and efficient service.

# Key Features
1. User Greeting and Authentication:
Initiates with a friendly greeting message.
Prompts users to provide their email or phone number for verification.
Utilizes LLMs to authenticate user information and retrieve relevant details.

2. Graph-based LLM Implementation:

Structures the support flow using utility functions for managing outputs and inputs.
Defines edges and nodes to create a graph representing the support process.
Validates and parses user inputs to extract necessary information.

3. Conversation Flow Management:

Nodes manage the dialogue flow, deciding the next steps based on user responses.
Implements logic to follow appropriate edges depending on user inputs.

4. Edge Execution:

Defines specific edges with conditions and parsing logic.
Uses LLMs for input validation and information extraction.

5. Contextual Information Retrieval:

Builds knowledge bases for different subscription types.
Implements multi-retrieval chains to select and retrieve relevant information based on user subscriptions.

6. Simulated Call Handling and Summarization:

Simulates phone interactions, retrieving user history and subscription data.
Uses LLMs to transcribe and summarize calls, generating detailed support tickets.

7. Comprehensive Application Integration:

Integrates all components into a unified customer support system.
Develops a user-friendly interface for seamless interaction with the application.

# Data Utilization

Employs diverse datasets, including user logs, PDF knowledge bases, and database-stored user information.

# Technology Stack

Programming Language: Python 3.10.4

Libraries: pandas, numpy, spacy, sentence transformers, annoy, flask, AWS

Modular Code Structure

Agents: Handles customer support agent functionalities.

Assets: Includes audio and text files for free and paid subscriptions.

Data: Manages data handling, chat functionalities, graph operations, and validation.

Tools: Contains scripts for audio transcription, user response handling, and database management.

UI: Manages graph rendering for the user interface.

Graph: Houses modules for graph-based structures.

# Learning Outcomes

Understanding the role of LLMs in automating customer support.

Exploring the LangChain framework.

Structuring multi-step support flows using LangChains.

Developing custom output parsers.

Performing ReACT prompt engineering.

Implementing Directed Acyclic Graphs.

Creating workflows using LLMs as graphs.

Using retrieval augmented generation for contextual information retrieval.

Implementing multi-retrieval chains for database interactions.

Utilizing the Whisper model for speech-to-text in voice interactions.

# For the code, please change the branch to 'master'  
