# Car Battery Data Scraper (Arabic E-commerce)

This project is a Python-based web scraper designed to extract detailed product data about **car batteries** from an Arabic e-commerce website.

## 📌 Features

- Extracts battery name, brand, capacity (Ah), cold cranking amps (CCA), size, price, and availability.
- Supports Arabic text content.
- Saves data in a clean and structured Excel file.
- Handles multiple pages and categories if needed.

## 🛠️ Technologies Used

- `requests` – for sending HTTP requests
- `BeautifulSoup` – for parsing HTML content
- `pandas` – for organizing and exporting data
- `openpyxl` – for Excel output (if used)

## 📂 Output

The final output is an Excel sheet containing:

| Battery Name | Brand | Capacity (Ah) | CCA | Size | Price | Availability |
|--------------|--------|----------------|-----|------|-------|--------------|
| [Sample Data] | ...    | ...            | ... | ...  | ...   | ...          |

> You can also download the [PDF version here](link-if-any).

## 📸 Screenshot

![Preview](path-to-screenshot.png)

## 🚀 How to Run

```bash
pip install -r requirements.txt
python scrape.py
