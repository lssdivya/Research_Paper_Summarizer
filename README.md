# Research Paper Summarizer using OpenAI API

This project provides a powerful, AI-driven tool to **automatically summarize research papers (PDFs)** using the OpenAI GPT API. Designed for students, researchers, and professionals, it helps extract, chunk, and simplify dense academic content into concise, human-readable summaries.

> ✨ "Turn 20-page research papers into 2-minute reads."

## Features

- Upload any academic PDF paper
- Extracts full text using PyMuPDF
- Splits content into manageable chunks (based on tokens)
- Sends chunks to OpenAI's GPT API for summarization
- Combines all chunk summaries into one final abstract
- API key stored securely via environment variable


## ⚙️ Setup Instructions

1. **Clone the repository**

```bash
git clone https://github.com/lssdivya/research-paper-summarizer.git
cd research-paper-summarizer

2. **Install dependencies**

pip install -r requirements.txt

3. **Set your OpenAI API Key**

Store it securely using environment variables:
Linux/macOS:
export OPENAI_API_KEY='your-api-key-here'
Windows (CMD):
set OPENAI_API_KEY=your-api-key-here

4. **Run the summarizer**

python summarizer.py
You’ll be prompted to enter a PDF file path. The output will display summaries for each chunk and a final abstract at the end.

📚 Tech Stack

Python 3.8+
OpenAI API
PyMuPDF for PDF extraction
tiktoken for token counting
nltk or custom logic for sentence splitting
os and dotenv for secure key management


