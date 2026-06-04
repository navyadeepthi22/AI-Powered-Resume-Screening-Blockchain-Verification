# AI-Powered Resume Screening & Blockchain Certificate Verification System

## 📌Overview

This project integrates Artificial Intelligence (AI), Natural Language Processing (NLP), and Blockchain technology to streamline recruitment and certificate verification processes. The system automatically analyzes resumes, ranks candidates based on job requirements, and verifies certificates using blockchain-based records.

## 🎯Problem Statement

Traditional recruitment processes are time-consuming and prone to human bias. Certificate fraud is another major challenge faced by organizations. This project addresses both issues by automating candidate screening and enabling secure certificate verification.


## 🚀Features

* Automated resume screening
* Candidate ranking and shortlisting
* NLP-based text analysis
* Blockchain certificate verification
* Secure and transparent validation process
* User-friendly interface

## 🛠️Technologies Used

### Backend
Python 3.10+ — Core runtime
Flask — Web framework, session management, routing
SQLite3 — User authentication database
Werkzeug.security — Password hashing (PBKDF2:SHA256)
PyPDF2 — PDF text extraction
scikit-learn — TF-IDF Vectorizer + cosine similarity
NLTK — English stopwords removal
Web3.py — Ethereum blockchain interaction
hashlib — SHA-256 hashing for certificates
### Certificate Processing
pytesseract — OCR for image-based certificates
Pillow — Image processing
BeautifulSoup — HTML parsing for issuer verification
requests — HTTP client for verification APIs
### Messaging
Twilio WhatsApp API — Outbound requests + inbound webhook
### Blockchain
Solidity ^0.8.0 — Smart contract language
Ganache — Local Ethereum blockchain
web3.py — Python ↔ Ethereum bridge
solc-x — Solidity compiler
### Frontend
HTML5 / CSS3 / JavaScript ES6+ — SPA frontend
Custom CSS — Hand-crafted dark theme with glassmorphism
Font Awesome 6.5.1 — Icons
Fontshare CDN — Typography (Cabinet Grotesk, General Sans)

## System Workflow

1. Candidate uploads resume.
2. Resume is processed using NLP techniques.
3. Machine learning model evaluates and ranks candidates.
4. Certificate data is verified using blockchain records.
5. Recruiter receives screening and verification results.

## Project Screenshots
## Project Workflow

![Data Flow Diagram](diagrams/data_flow_diagram.jpeg)

## Output

![Output](screenshorts/output.jpeg)


## Future Enhancements

* Advanced NLP models
* Public blockchain deployment
* Cloud deployment
* Real-time recruitment integrations

## Project Showcase Repository

This repository serves as a project showcase containing documentation, screenshots, and project artifacts.

The implementation/source code for the project is available at:

https://github.com/Shashanth-V/AI-Resume-Screening

