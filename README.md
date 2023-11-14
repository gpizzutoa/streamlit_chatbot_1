# streamlit_chatbot_1

This repository contains the source code for a ChatGPT-like clone application built using OpenAI's GPT models and Streamlit for the web interface.

## Getting Started

### Prerequisites

Before you can run this application, you need to have the following libraries installed:

- `openai`: The official OpenAI Python client library for accessing the GPT models.
- `streamlit`: An open-source app framework for Machine Learning and Data Science projects.

### Configuration

In the *constants.py* file, set the OPENAI_API_KEY variable with your OpenAI API key.

### Running the Application

To run the application, navigate to the project directory and execute the following command:

## How It Works
- The application uses Streamlit to create a web interface for user interactions.
- When a user inputs a message, it's sent to OpenAI's GPT model specified in st.session_state["openai_model"] (default is gpt-3.5-turbo).
- The GPT model generates a response based on the conversation history, which is then displayed on the interface.
