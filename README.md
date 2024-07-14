# Google Gemini API Integration

Integrate Google Gemini API using Flask.

## Prerequisites

- Python 3.x
- Flask
- `dotenv`
- `langchain-core`
- `langchain-google-genai`

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
    python app.py
    ```
    Access at `http://localhost`.

## API Endpoints

- `GET /`: Main web interface.
- `POST /api/generate`: Generate a response from Google Gemini.
  - **Request:**
    ```json
    {
      "contents": "Your input text",
      "model": "Model name"
    }
    ```
  - **Response:** Streamed generated text.
- `GET /<path>`: Serve static files from `web` directory.

## Directory Structure

```
├── app.py
├── requirements.txt
├── .env
└── web
    └── index.html
```

## Contact

- **Email**: jayakuma006@mymail.sim.edu.sg
- **LinkedIn**: [Akilesh Jayakumar](https://www.linkedin.com/in/akileshjayakumar/)
- **GitHub**: [Akilesh Jayakumar](https://github.com/akileshjayakumar)
