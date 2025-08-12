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

multimodal-llm-doc-parser/ <br>
│<br>
├── data/                   # Sample input PNG files<br>
├── src/                    # Python source code<br>
│   ├── __init__.py
│   ├── ocr_easyocr.py               # OCR functions<br>
│   ├── llm_integration.py   # Hugging Face LLM calls<br>
│   ├── utils.py<br>
│   ├── preprocessing.py             # Helper functions<br>
│<br>
├── notebooks/<br>
│   └── image_parser.ipynb     # Colab-ready notebook<br>
│<br>
├── requirements.txt<br>
├── README.md<br>
└── .gitignore<br>



## Roadmap
- Add PDF-to-PNG preprocessing
- Support handwriting recognition
- Enhance LLM reasoning for table extraction
- Deploy as a lightweight API
