# ITPM Assignment 1 - Option 2

## Student Details
- Name: JAYAWARDANA V K A
- Registration Number: IT23864306

## Project Overview
This project focuses on performing functional and usability testing on the Pixelssuite website (https://www.pixelssuite.com/). The objective is to verify that the website features work correctly and provide a user-friendly experience.

## Features Tested
- Document conversion
- PDF editing
- Image resizing
- Cropping
- Compression
- Image format conversion
- Meme generation
- Color picker
- Image rotation
- Image flipping

## Testing Approach
- 35 Manual Test Cases (Functional & Negative/Positive scenarios)
- 1 Automated Test Case using Playwright
- CSV file used to record automation execution results

## Tools Used
- Python
- Playwright
- OpenPyXL
- Google Chrome

## How to Run
1. Install dependencies:
   pip install playwright openpyxl
2. Install browser:
   python -m playwright install
3. Run test:
   python image_preview_test.py --url "https://www.pixelssuite.com/convert-to-png" --slow-mo-ms 2000

## Files Included
- Manual_Test_Cases_for_Option_2.xlsx
- execution_results.csv
- Playwright automation scripts.
