# Computational Characterization of Drug Safety Information from Product Labels

This Python program analyzes drug safety information extracted from product labels using image processing and optical character recognition (OCR) techniques. The script aims to validate medication names, determine safety levels, and provide insights for risk assessment.

## Features

- **Image Processing:** Utilizes OpenCV to extract text data from product label images.
- **OCR with Pytesseract:** Employs Pytesseract for optical character recognition to extract text information.
- **Medication Name Validation:** Validates medication names against a dataset, ensuring accuracy in analysis.
- **Safety Level Determination:** Determines safety levels for medications, aiding in informed risk assessment.
- **Interactions and Missing Dose Analysis:** Assesses interactions and provides guidance for missed doses.



## Instructions

- `drug_safety_analysis.py`: Main Python script for drug safety analysis.
- `back.jpeg`: Sample product label image for analysis.
- `Drugs.xlsx`: Dataset containing medication information for validation.

## Example Output

- Extracts medication names and checks their presence in the dataset.
- Evaluates interactions, guidance for missed doses, and safety levels.
- Displays safety level color codes (red, yellow, purple, blue) based on analysis.



