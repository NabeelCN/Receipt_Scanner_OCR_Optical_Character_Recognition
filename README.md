Project Overview

This project is a Receipt Scanner OCR (Optical Character Recognition) system developed using Python, OpenCV, and PyTesseract. The application extracts text from receipt images and processes the information automatically. It helps in digitizing receipts, reducing manual data entry, and improving document management.

Objectives
Read and process receipt images
Extract text using OCR techniques
Clean and preprocess extracted text
Identify important information such as dates, amounts, and invoice numbers
Store extracted data in a structured format
Technologies Used
Python
OpenCV (cv2)
PyTesseract
EasyOCR (optional)
Regular Expressions (Regex)
Pandas
NumPy
Jupyter Notebook / Google Colab
Project Workflow
Data Collection (Receipt Images)
Image Preprocessing
Text Extraction using OCR
Text Cleaning and Processing
Information Extraction using Regex
Store Extracted Data
Display Results
Features
Extracts text from receipt images automatically
Supports multiple receipt formats
Identifies important fields such as:
Date
Total Amount
Invoice Number
Store Name
Reduces manual data entry
Converts unstructured receipt data into structured information
OCR Tools Used
PyTesseract
Converts images into machine-readable text.
EasyOCR (Optional)
Provides improved text extraction for complex receipt images.
Project Structure
Receipt_Scanner_OCR_Optical_Character_Recognition/
│
├── data/                   # Receipt images
├── notebooks/              # Jupyter/Colab files
├── outputs/                # Extracted text files
├── images/                 # Sample receipts and screenshots
├── src/                    # Python scripts
├── README.md
└── requirements.txt
Results

The system successfully extracts text from receipt images and identifies key information with good accuracy after preprocessing and text cleaning.

Future Improvements
Improve OCR accuracy for low-quality images
Extract additional fields automatically
Build a web application using Flask or Streamlit
Integrate with databases for receipt management
Support multiple languages and currencies
Author

Nabeel C N
