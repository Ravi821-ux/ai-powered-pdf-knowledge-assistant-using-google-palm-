# ai-powered-pdf-knowledge-assistant-using-google-palm-

DocuQuery AI is an AI-powered document analysis tool that uses **Google Gemini AI** to help users extract and interact with content from PDFs and DOCX files. This application, built with **Streamlit**, allows users to upload documents and ask AI-powered questions based on their content.

## Features

- 📄 **Research Paper Simplifier**: Extracts text from PDFs/DOCX files and allows AI-powered Q&A.
- 📊 **Price List Analyzer**: Supports CSV/XLSX price lists for basic data analysis.
- 📝 **Resume Matcher (Upcoming)**: Matches resumes against job descriptions.

## Installation

### 1. Clone the repository:

```sh
git clone https://github.com/yourusername/docuquery-ai.git
cd docuquery-ai
```

### 2. Install dependencies:

```sh
pip install -r requirements.txt
```

### 3. Set up environment variables:

Create a `.env` file in the project directory and add:

```sh
GEMINI_API_KEY=your_api_key_here
```

### 4. Run the application:

```sh
streamlit run docuquery_ai.py
```

## Usage

1. Upload a PDF/DOCX file.
2. Extracted text will be displayed.
3. Ask questions related to the document.
4. AI will generate relevant responses.

## Dependencies

- `streamlit`
- `PyPDF2`
- `python-docx`
- `google-generativeai`
- `dotenv`

##

## Contributing

Feel free to contribute! Fork the repo, make your changes, and submit a pull request.

---

Made with ❤️ by [Ravi Swaroop]

