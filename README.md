# Ollama Streamlit Chatbot 🤖

## Project Description
This is an interactive Streamlit application that provides a simple Q&A chatbot interface powered by Ollama, allowing users to interact with various open-source language models.

## Features
- Select from multiple open-source language models (Mistral, Gemma, Phi3, Llama3.2)
- Adjust model temperature for response creativity
- Control maximum token output
- User-friendly Streamlit interface

## Prerequisites
- Python 3.8+
- Ollama installed locally
- Required Python packages (see `requirements.txt`)

## Installation

1. Clone the repository:
```bash
git clone https://your-repo-url.git
cd your-repo-name
```

2. Create a virtual environment:
```bash
python -m venv venv
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

4. Set up environment variables:
- Create a `.env` file in the project root
- Add your Langchain API key:
```
LANGCHAIN_API_KEY=your_langchain_api_key
LANGCHAIN_PROJECT=your_project_name
```

## Running the App
```bash
streamlit run Ollama_app.py
```

## Configuration
- Use the sidebar to select different language models
- Adjust temperature to control response randomness
- Set maximum token limit for responses

## Dependencies
- Streamlit
- Langchain
- OpenAI
- Python-dotenv
- Ollama

## Contributing
Contributions are welcome! Please feel free to submit a Pull Request.

## License
[Specify your license here]

## Acknowledgments
- Ollama for providing open-source language models
- Streamlit for the interactive web application framework
