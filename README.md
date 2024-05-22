### RESUME PARSER

A resume parser that extracts useful information from a resume using Natural Language Processing (NLP) and a model from Hugging Face.

* Supports PDF( with images) and DOCX formats
* Uses the Hugging Face Transformers library for NLP
* Uses the pytesseract library for OCR (Optical Character Recognition)

## Features:

Extracts the following information from a resume:

- Full name
- Email
- Linkedin Url
- Contact number
- Education
- Skills
- Experience
- other info


## Install the pytesseract library:
- For Windows, download and install the pytesseract package from the following link: https://github.com/UB-Mannheim/tesseract/wiki
- For Ubuntu, run the following command:

sudo apt-get install tesseract-ocr

- Set the path to the pytesseract executable in the tesseract_path variable in the resume_parser.py file.


### The extracted information will be printed to the console and saved to a JSON file in the output directory.

### Libraries Used
pdf2image: A library for converting PDF files to images.

transformers: A library for NLP tasks using pre-trained models.

pytesseract: A library for OCR.

os: A library for interacting with the operating system.

json: A library for working with JSON data.

docx: A library for working with DOCX files.

docx2pdf: A library for converting DOCX files to PDF.

PIL: A library for working with images.

