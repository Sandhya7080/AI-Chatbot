# AIChatbot: A Conversational AI Powered by BlenderBot

This repository contains the code for an AI Chatbot powered by the **BlenderBot** model from Facebook AI. The chatbot is designed to handle dynamic and interactive conversations with users, providing intelligent responses. Built using the **Transformers** library by **Hugging Face**, it supports flexible conversation flow, maintains conversation history, and utilizes state-of-the-art natural language processing (NLP) techniques to generate meaningful dialogue.

## Features:

- **BlenderBot Integration**: The core of the chatbot is powered by Facebook's **BlenderBot-400M-distill**, a fine-tuned conversational AI model known for its human-like dialogues.
  
- **Dynamic Conversation Flow**: Maintains and updates conversation history to generate responses based on the context of previous interactions.
  
- **Tokenization and Encoding**: Utilizes Hugging Face's tokenizer to efficiently process and encode user inputs and conversation history for the model.
  
- **Gradio Interface**: Features a simple and interactive web interface powered by **Gradio**, enabling easy user interaction with the chatbot.
  
- **Response Generation**: The chatbot generates responses by combining previous conversation history and current user input.

## Installation

To get started with this project, clone the repository and install the required dependencies:

```bash
git clone https://github.com/yourusername/AIChatbot.git
cd AIChatbot
pip install -r requirements.txt
```

# How to Run

To launch the chatbot and start interacting with it, follow these steps:

1. Clone the repository and install dependencies as shown in the **Installation** section.

2. Once all dependencies are installed, execute the `chatbot.py` script:

    ```bash
    python chatbot.py
    ```

3. This will start a **Gradio** interface in your browser. You can interact with the chatbot by typing messages in the provided input box.

## Technologies Used

- **Transformers**: Hugging Face's transformer library for loading and using the **BlenderBot** model.
  
- **Gradio**: For creating the interactive web interface.
  
- **Flask**: For handling HTTP requests and managing server-side interactions.
  
- **Python**: The primary programming language for this project.
