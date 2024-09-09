# Google Gemini API Integration

This repo is for me to explore and experiement with Google Gemini API.

## Tech Stack

1. **[Python3](https://www.python.org/downloads/)** – The programming language used for backend development
2. **[Flask](https://flask.palletsprojects.com/en/latest/installation/)** – A lightweight WSGI web application framework
3. **[python-dotenv](https://pypi.org/project/python-dotenv/)** – Manages environment variables in Python applications via `.env` files
4. **[langchain-core](https://python.langchain.com/docs/get_started/installation)** – The core package for building language models with LangChain
5. **[langchain-google-genai](https://python.langchain.com/docs/integrations/providers/google_genai)** – Enables integration with Google GenAI for advanced language model functionality

## Setup

1. **Clone the Repo**
    ```bash
    git clone https://github.com/akileshjayakumar/my-gemini-api-app
    cd my-gemini-api-app
    ```
2. **Install Dependencies**
    ```bash
    pip install -r requirements.txt
    ```
3. **Configure API Key**
    ```plaintext
    GOOGLE_API_KEY=your_google_api_key
    ```
4. **Run the App**
    ```bash
    python3 app.py
    ```
