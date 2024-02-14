# Automated Medical Forms Extraction for Efficient Healthcare Data Management (Confidentiality-Preserving)

## Description

This project demonstrates a secure and efficient approach to extracting and structuring data from medical forms using a combination of optical character recognition (OCR) and advanced deep learning techniques. It prioritizes patient privacy by applying data anonymization and other confidentiality-preserving measures.

**Key Features:**

- **Handles diverse image formats:** Extracts data from various image types, including scanned PDFs, JPEGs, PNGs, and more.
- **Robust OCR:** Employs PyTesseract for accurate text recognition from even challenging handwritten forms.
- **Efficient data structuring:** Leverages libraries  to transform extracted data into well-organized JSON format, facilitating analysis and integration with clinical databases.
- **Comprehensive data validation:** Implements regular expressions and other validation techniques to ensure data integrity and consistency.
- **Flexibility:** Allows customization based on specific form types and data extraction requirements.
- **Confidentiality-focused:** Prioritizes patient privacy through data anonymization (e.g., using techniques like pseudonymization) and secure handling of sensitive information.

## Dependencies

- pytesseract
- regular expression
- google generative ai
- PIL

## Running the Code

Before executing the provided code snippets, follow these steps:

1. **Image Preparation:**
   - Download all the medical form images required for testing.
   - Place these images in the appropriate directory.

2. **Path Adjustment:**
   - Replace all image paths in the code with the paths of the images stored on your computer.

3. **Notebook Execution:**

   - **Using Gemini Vision Pro Model:**
     - Open the `Gemini_for_better_extraction_of_data_the_bug_busters.ipynb` notebook.
     - Execute the notebook to utilize Google's latest Gemini Vision Pro model for enhanced data extraction.

   - **Using Pytesseract and Regular Expressions:**
     - Open the `official code.ipynb` notebook.
     - Execute the notebook to explore data extraction using pytesseract and regular expressions.

By following these steps, you can efficiently test and evaluate the functionality of the provided code for medical form data extraction.


Thank you for reading, much love. take care.
