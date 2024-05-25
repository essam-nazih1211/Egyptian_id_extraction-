# Egyptian_id_extraction-
# Egyptian-ID Extraction using OCR and Card-Rectification

## Project Overview

This project provides a comprehensive solution for extracting and rectifying data from Egyptian ID cards using OCR (Optical Character Recognition) and advanced image processing techniques. The main components of this project are:

1. **Card Rectification Algorithm**: Utilizes the UNetRNN model to correct the orientation and perspective of the ID card image.
2. **Comparison with Reference Image**: Aligns the corrected ID card image with a reference image to ensure proper orientation and format.
3. **Text Detection**: Uses ArabicOCR for detecting text fields on the ID card.
4. **ID Number Extraction**: Employs Tesseract-OCR to accurately extract the ID number.

## Features

- **Card Rectification**: Automatically corrects the orientation and perspective of ID card images.
- **Reference Image Comparison**: Ensures the output image is correctly oriented and formatted.
- **Arabic Text Detection**: Recognizes and extracts Arabic text from the ID card.
- **ID Number Extraction**: Accurately identifies and extracts the ID number using Tesseract-OCR.

## Components

### 1. Card Rectification

The card rectification process involves the following steps:
- **Input Image**: The raw ID card image.
- **UNetRNN Model**: Corrects the orientation and perspective of the ID card.
- **Output Image**: A rectified version of the ID card image.

### 2. Comparison with Reference Image

- **Input**: The rectified ID card image.
- **Reference Image**: A correctly oriented and formatted reference image.
- **Alignment**: The rectified image is compared with the reference image to ensure proper orientation and layout.

### 3. Text Detection (ArabicOCR)

- **Input**: The aligned ID card image.
- **ArabicOCR**: Detects and extracts Arabic text fields from the ID card.

### 4. ID Number Extraction (Tesseract-OCR)

- **Input**: The aligned ID card image.
- **Tesseract-OCR**: Detects and extracts the ID number from the ID card.


