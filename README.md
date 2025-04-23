# PDF Knowledge Bot

Please download Zip Folder. 

A conversational AI assistant that allows users to ask questions about PDF content and get accurate, referenced answers.

![PDF Knowledge Bot Screenshot](screenshot.png)

## Features

- 📑 Upload and analyze PDF documents
- 🔍 Ask questions in natural language about PDF content
- 💬 Chat-based interface for seamless interaction
- 🧠 AI-powered responses with source references
- 🌐 Web-based UI accessible from any browser

## Project Structure

```
chatbot-KseminGRC/
├── backend/             # Flask backend API
├── ChatBot/             # React frontend application
└── uploaded_pdfs/       # Storage for uploaded PDF files
```

## Technology Stack

### Frontend
- React 19
- Vite
- CSS3
- Fetch API for HTTP requests

### Backend
- Flask (Python)
- LangChain for LLM integration
- PyPDF for PDF parsing
- Vector embeddings for semantic search

## Setup Instructions

### Prerequisites
- Node.js 18+ and npm
- Python 3.9+
- pip (Python package manager)

### Backend Setup
1. Navigate to the backend directory:
   ```bash
   cd backend
   ```

2. Install the Python dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Start the Flask server:
   ```bash
   python main.py
   ```
   The backend will run on http://localhost:5000

### Frontend Setup
1. Navigate to the ChatBot directory:
   ```bash
   cd ChatBot
   ```

2. Install the dependencies:
   ```bash
   npm install
   ```

3. Start the development server:
   ```bash
   npm run dev
   ```
   The frontend will be available at http://localhost:5173

## Usage

1. Ensure both backend and frontend servers are running
2. Upload PDF documents through the interface
3. Start asking questions about the PDF content
4. Review the AI's responses with highlighted source references

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- Built with React and Flask
- Powered by advanced NLP techniques
- Uses vector search for accurate information retrieval

- Please Download Zip 📂 
