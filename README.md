# Enhanced Q&A Chatbot with OpenAI

This repository contains a Streamlit application for an enhanced Q&A chatbot that leverages OpenAI models and LangChain. The app allows users to interact with the chatbot and get responses based on their queries.

## Features

- User-friendly interface to interact with the chatbot.
- Option to select the Open Source model (Llama 3.1).
- Adjustable response parameters (Temperature and Max Tokens).
- Utilizes LangChain for prompt templates and response generation.

## Installation

1. Clone the repository:

```sh
git clone https://github.com/your-username/enhanced-qa-chatbot.git
cd enhanced-qa-chatbot
Install the required dependencies:
sh
Copy code
pip install -r requirements.txt
Create a .env file in the root directory and add your LangChain API key:
makefile
Copy code
LANGCHAIN_API_KEY=your_langchain_api_key
Usage
Run the Streamlit app:
sh
Copy code
streamlit run app.py
Open your web browser and go to http://localhost:8501 to interact with the chatbot.
Configuration
Select Open Source Model: Choose the Open Source model from the sidebar (currently supports Llama 3.1).
Adjust Response Parameters:
Temperature: Adjust the creativity of the responses.
Max Tokens: Set the maximum length of the responses.
File Structure
app.py: The main application script.
requirements.txt: List of dependencies.
.env: Environment file for storing API keys (not included in the repo).
Contributing
Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

License
This project is licensed under the MIT License. See the LICENSE file for more details.

Acknowledgements
Streamlit
OpenAI
LangChain
