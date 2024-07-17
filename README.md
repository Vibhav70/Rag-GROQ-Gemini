# RAG using GROQ and Gemini

This project demonstrates a Retrieval-Augmented Generation (RAG) application using the GROQ and Gemini (Google Generative AI) models. The application allows users to upload PDF documents, which are then processed to create a vector store for efficient information retrieval. Users can ask questions about the content of the uploaded documents, and the system will provide accurate responses based on the document context.

## Features

- Upload PDF files and process them to create a searchable vector store.
- Ask questions about the uploaded documents and get precise answers.
- Utilizes GROQ for language modeling and Gemini for embeddings.

## Getting Started

### Prerequisites

- Python 3.8 or later
- [GROQ API Key](https://console.groq.com/keys)
- [Google Generative AI (Gemini) API Key](https://ai.google.dev/)

### Setup

1. Clone the repository:

   ```bash
   git clone https://github.com/Vibhav70/Rag-GROQ-Gemini.git
   cd Rag-GROQ-Gemini

2. Make the python environment

   ```bash
   python3 -m venv env
   source env/bin/activate  # On Windows use `env\Scripts\activate`

3. Install the required Packages
   
   ```bash
   pip install -r requirements.txt

5. Make a .env file and write the following
   
   ```bash
   "GROQ_API_KEY" = your_groq_api_key
   "GOOGLE_API_KEY" = your_google_api_key

6. Run the main script
   ```bash
   streamlit run main.py
