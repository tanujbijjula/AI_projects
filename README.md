---
title: personal_project
app_file: apps.py
sdk: gradio
sdk_version: 5.31.0
---
# AI_projects

🔍 Project Overview
*Handles user inquiries related to your profile.
*Records unanswered questions and user details via Pushover API.
*Uses OpenAI's local model (llama3.2) for chat generation.
*Extracts and processes information from the CV and summary file.
*Interfaces with users via Gradio.

⚙️ Technologies Used
1. Environment Variable Management (dotenv)
 Loads environment variables from a .env file, useful for managing sensitive API keys and configurations.
2. OpenAI API Usage (openai)
 Interfaces with OpenAI's API for generating AI-powered responses (connected via local Ollama model: llama3.2).
3. Data Handling & Processing
 json: Manages structured data for API interactions.
 os: Handles file path management and environment variables.
 requests: Facilitates HTTP requests for sending API calls.
4. PDF Processing (pypdf)
 Extracts text from a PDF (cv.pdf) to analyze LinkedIn profile details.
5. Gradio for AI Chat Interface (gradio)
 Provides a web-based UI for interaction with the AI model.
6. Pushover API for Notifications (requests)
 Sends push notifications using Pushover API.
7. Custom AI Model Handling
 Uses a locally hosted Llama 3.2 model via Ollama for AI-driven chatbot . . responses.
8. Tool-Calling Mechanism
 Implements function calling for structured interaction, recording user . details and unanswered questions.
