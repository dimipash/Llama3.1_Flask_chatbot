## Chatbot App

- This is a simple chatbot app built using Flask and the LangChain library. The app allows users to interact with a chatbot that uses the Llama 3.1 language model, running locally using Ollama, to respond to user queries.

### Features

- Users can input queries in a text box on the home page
- The chatbot responds to user queries using the Llama 3.1 language model locally.
- The chatbot's responses are formatted using Markdown bold syntax and converted to HTML strong tags
- The app logs errors and exceptions to the console

### Getting Started

- Clone this repository to your local machine
- Install the required dependencies by running pip install -r requirements.txt
- Run the app by executing python app.py
- Open a web browser and navigate to http://localhost:5000 to access the chatbot

### Configuration

- The LLaMA 3.1 language model is used by default. You can change this by modifying the model parameter in the initialise_llama3_1 function.
- The chatbot's prompt is defined in the create_prompt function. You can modify this to change the chatbot's behavior.

![Chatbot App Screenshot](https://github.com/dimipash/Llama3.1_Flask_chatbot/blob/main/screenshot.png)
