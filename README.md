# PolishGPT
Document Upload and Q&A System
Description
This project is a Flask-based web application that allows users to upload documents in various formats (including DOCX, PDF, PPTX, XLSX, and images). Once uploaded, the application extracts text from these documents and enables users to ask questions related to the content. The responses are generated using the OpenAI API, integrating advanced AI-driven text analysis.

Features
Document Upload: Supports multiple file formats for upload and processing.
Text Extraction: Extracts text from uploaded documents using Python libraries like python-docx, PyPDF2, and pytesseract for OCR.
Interactive Q&A: Users can ask questions regarding the content of the uploaded documents, and receive AI-generated answers.
Technology Stack
Flask: For the web server and routing.
OpenAI API: To generate responses to user questions.
Python Libraries: python-docx, PyPDF2, openpyxl, python-pptx, PIL, pytesseract for file handling and text extraction.
Installation Guide
Clone the repository and install the required Python packages:

pip install -r requirements.txt
