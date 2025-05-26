# MultiPDF Chatter: Gemini-Powered PDF Chat Assistant

An interactive Streamlit web app that lets you chat with multiple PDF files using Google’s Gemini model via LangChain. Upload your documents and ask questions — the app reads, understands, and responds with relevant answers.

## 🚀 Features

- 📄 Upload and chat with multiple PDFs
- 🤖 Uses Google Gemini (via `ChatGoogleGenerativeAI`)
- 🔗 Powered by LangChain for conversational memory
- 💬 Streamlit UI for easy interaction
- 🌡️ Adjustable temperature for response creativity

## 🛠️ Tech Stack

- Python
- Streamlit
- LangChain
- Google Generative AI (`gemini-1.5-flash`)
- PyMuPDF / PDFMiner / pdfplumber (PDF parsing)

## 🔧 Installation
git clone https://github.com/yourusername/multipdf-chatter.git
cd multipdf-chatter
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
pip install -r requirements.txt

## How It Works
  1.Upload multiple PDF files.
    
  2.The app extracts and embeds text using LangChain.
  
  3.Asks questions in natural language.
  
  4.Gemini responds contextually based on your documents.

