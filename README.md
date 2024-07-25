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

## Contributing

Your contributions are welcome! If you have ideas for improvements or new features:

1. **Fork the Repository**
2. **Create a Branch:**
   ```bash
   git checkout -b feature-branch
   ```
3. **Commit Changes:**
   ```bash
   git commit -am 'Add new feature: description'
   ```
4. **Push to Branch:**
   ```bash
   git push origin feature-branch
   ```
5. **Submit a Pull Request**

## Contact

- **Email:** [jayakuma006@mymail.sim.edu.sg](mailto:jayakuma006@mymail.sim.edu.sg)
- **LinkedIn:** [Akilesh Jayakumar on LinkedIn](https://www.linkedin.com/in/akileshjayakumar/)
- **GitHub:** [Akilesh Jayakumar on GitHub](https://github.com/akileshjayakumar)
