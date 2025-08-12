## Overview
This repository contains the codebase for my Bachelor's thesis project: **Multimodal Large Language Model (LLM) guided document parser**.  
The goal is to process **image-based documents** (PNG), extract relevant text and structure via **OCR**, and interpret it using **LLMs** to produce structured, human-readable output.

---

##  Features
-  PNG document ingestion
-  OCR using **EasyOCR** and **Tesseract**
-  Multimodal LLM integration (Hugging Face Transformers)
-  Output as structured JSON or text
-  Ready to run on **Google Colab** or locally
-  Modular pipeline for future datasets

---

## Folder Structure
multimodal-llm-doc-parser/
│
├── data/                   # Sample input PNG files
├── src/                    # Python source code
│   ├── __init__.py
│   ├── ocr_easyocr.py               # OCR functions
│   ├── llm_integration.py   # Hugging Face LLM calls
│   ├── utils.py
│   ├── preprocessing.py             # Helper functions             # Helper functions
│
├── notebooks/
│   └── image_parser.ipynb     # Colab-ready notebook
│
├── requirements.txt
├── README.md
└── .gitignore



## Roadmap
- Add PDF-to-PNG preprocessing
- Support handwriting recognition
- Enhance LLM reasoning for table extraction
- Deploy as a lightweight API
