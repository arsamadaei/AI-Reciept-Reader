# AI Receipt Reader

An AI-powered tool that extracts text from your receipt images and organizes it into an Excel file for easier budgeting and financial tracking.

---

## Features
- Automatically extracts text from receipt images.
- Uses Google Generative AI + OCR for improved accuracy.
- Appends results into an **Excel table** with the following schema:
  - **Date**
  - **Item**
  - **Quantity**
  - **Price**
  - **Location**
- Saves everything into a structured `.xlsx` file for easy budgeting.

---

## Project Setup

1. Clone or download this repository.  
2. Create a folder named **`receipts/`** in the project root.  
   - Place all receipt images inside this folder.  
3. Ensure the main script **`Receipt Reader.py`** is located **outside** the `receipts/` folder.  
4. Get your **Google Generative AI API key** from [Google AI Studio](https://ai.google.dev/).  
   - Place your API key in the code where indicated.  

---

## Usage

Run the script with:

```bash
python3 "Receipt Reader.py"
