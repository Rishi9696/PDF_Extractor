# PDF_Extractor

# PDF Transaction Extractor

## Overview
This Python script is designed to extract transaction data from PDF files and save the data to an Excel file. It utilizes the `pdfplumber` library to read PDFs and `pandas` to manage and export the data.

## Features
- **Transaction Line Detection**: Uses regular expressions to accurately identify transaction lines within the PDF text.
- **Data Extraction**: Breaks down each transaction line into components like date, transaction type, description, amount, and balance.
- **Export to Excel**: Saves the extracted data into an Excel file using the `openpyxl` engine for easy analysis and record-keeping.

## Requirements
To run this script, you need to have Python installed along with the following libraries:
- `pdfplumber`
- `pandas`
- `re` (regular expression library, which is included by default in Python distributions)
- `openpyxl`

## Installation
Install the required Python libraries using pip:

## Usage
1. Place the PDF file you want to process in the same directory as the script or specify the path to the file.
2. Run the script by executing:
