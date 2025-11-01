# PPT Flag Checker Automation Using Selenium

This Python automation script uses **Selenium WebDriver** to scrape customer dial information from a web application, It navigates through multiple pages, extracts specific service data, checks for the **PPT Flag**, and saves the results into an Excel sheet.

---

## Features

- Automated login to the web system.
- Navigates through customer accounts.
- Handles overlays and dynamically loaded content.
- Extracts:
  - Dial count
  - Rate plan
  - Activation date
  - PPT flag status
  - Status and reason (if applicable)
- Saves results directly into an Excel file using `openpyxl`.
- Screenshots accounts missing data or causing errors.

---

## Steps

Logs into a web portal
Navigates dynamically
Checks each account
Detects a specific “PPT flag”
Writes findings back into Excel

---

## Tech Stack

- [Selenium]  for web automation
- [OpenPyXL] to read/write Excel files
- Python 3.x

---

## Author
Ahmed Essam – Automation Engineer using Python + Selenium
