# Google Gemini API Integration

This project demonstrates how to integrate with the Google Gemini API using a Flask web application. The application allows users to generate responses from the Google Gemini model using a simple web interface.

## Prerequisites

- Python 3.x
- Flask
- `dotenv` library
- `langchain-core`
- `langchain-google-genai`

## Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/google-gemini-integration.git
cd google-gemini-integration
```

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

### 3. Get Your Google API Key

Obtain your Google API key from [Google's Gemini API](https://g.co/ai/idxGetGeminiKey) and create a `.env` file in the root directory of your project with the following content:

```plaintext
GOOGLE_API_KEY=your_google_api_key
```

### 4. Run the Application

```bash
python app.py
```

By default, the application will run on port 80. You can change the port by setting the `PORT` environment variable.

### 5. Access the Web Interface

Open your web browser and navigate to `http://localhost`.

## API Endpoints

### `GET /`

Serves the main web interface.

### `POST /api/generate`

Generates a response from the Google Gemini model.

#### Request Body

```json
{
  "contents": "Your input text",
  "model": "Model name"
}
```

#### Response

Streamed response with the generated text.

### `GET /<path>`

Serves static files from the `web` directory.

## Example Usage

You can use the web interface to input text and receive generated responses from the Google Gemini model. The responses are streamed back to the client in real-time.

## Directory Structure

```
├── app.py
├── requirements.txt
├── .env
└── web
    └── index.html
```

- `app.py`: The main Flask application.
- `requirements.txt`: Python dependencies.
- `.env`: Environment variables file containing your Google API key.
- `web/index.html`: The main HTML file for the web interface.

## Contributing

Your contributions are welcome! If you have ideas for improvements or new features:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -am 'Add some feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Submit a pull request.

## Contact Information

For more information, please reach out to me at:

- **Email**: jayakuma006@mymail.sim.edu.sg
- **LinkedIn**: [Akilesh Jayakumar on LinkedIn](https://www.linkedin.com/in/akileshjayakumar/)
- **GitHub**: [Akilesh Jayakumar on GitHub](https://github.com/akileshjayakumar)

