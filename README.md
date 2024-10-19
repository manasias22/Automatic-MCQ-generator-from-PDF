## Natural Language Processing Course Project

# Automatic MCQ Generator from PDF Using NLP

## Overview

This project aims to develop an automated system that generates multiple-choice questions (MCQs) from PDF documents using Natural Language Processing (NLP) techniques. The tool is designed to facilitate educators and students by streamlining the question creation process from existing textual resources.

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Dataset](#dataset)
- [Output](#output)

## Features

- **PDF Parsing**: Extracts text from PDF documents.
- **NLP Techniques**: Utilizes NLP algorithms to analyze and generate MCQs.
- **Customizable Output**: Allows users to set parameters for question generation.
- **User-Friendly Interface**: Simple command-line or web interface for easy interaction.

## Technologies Used

- Python
- Natural Language Toolkit (nltk)
- spaCy
- PyPDF2 or pdfplumber
- Flask or Streamlit (for web interface)
- scikit-learn
- Jupyter Notebook (for development)

## Installation

To get started with the project, clone the repository and install the required dependencies.

```bash
git clone https://github.com/yourusername/automatic-mcq-generator.git
cd automatic-mcq-generator
pip install -r requirements.txt
```

## Usage

1. **Prepare Your PDF**: Ensure you have a PDF document ready for question generation.
2. **Run the MCQ Generator**: python mcq_generator.py --pdf_path path/to/document.pdf
3. **View Generated Questions**: The generated MCQs will be saved in a specified output format (e.g., text file or JSON).

## Dataset

This project does not require a specific dataset, as it generates questions based on the text extracted from PDF documents.
## Output: 
![Screenshot 2024-10-08 223630](https://github.com/user-attachments/assets/0612f90f-478b-48a3-a79a-e387a4abf0d5)
## 4.3.1 Input Text
![Screenshot 2024-10-08 223505](https://github.com/user-attachments/assets/5c155b07-db35-41dc-86c7-58eb3f59b6cb)
## 4.3.2 Interface to Upload File in PDF format
![Screenshot 2024-10-08 223601](https://github.com/user-attachments/assets/93ac106f-3cb5-4c42-a31f-5af6ed7c532f)
## 4.3.3 Interface showing Pdf uploaded successfully
![Screenshot 2024-10-08 223708](https://github.com/user-attachments/assets/8beea56f-6021-4fa0-85dc-ffeb4bb48f4e)
## 4.3.4 Interface showing genarated MCQ Questions with Answers
