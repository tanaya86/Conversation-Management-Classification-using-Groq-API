# Conversation-Management-Classification-using-Groq-API
# Overview
This project demonstrates two core tasks using Groq API with its OpenAI-compatible SDK:
Conversation Management with Summarization – maintaining conversation history, truncation, and periodic summarization.
JSON Schema Classification & Information Extraction – extracting structured details from user chats using OpenAI function-calling format.
The work is implemented in a Google Colab notebook (Python, no external frameworks). Outputs are validated and logged with clean explanations.
# Features
# Task 1 – Conversation Management & Summarization
Maintain a running conversation history of user–assistant chats.
Truncation options:
Limit by last n turns.
Limit by character length.
Periodic summarization:
Summarize after every k-th run.
Replace older messages with summary + keep recent context.
Demonstrated with multiple conversation samples and varying settings.
# Task 2 – JSON Schema Classification
Define a JSON schema with 5 fields: name, email, phone, location, age.
Use Groq API’s OpenAI-compatible function calling for structured extraction.
Validate outputs against the schema.
Demonstrated with 3+ sample chats.
