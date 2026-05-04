# Singlish Transliteration – Playwright Test Automation

Tests for IT3040 Assignment 1 – Transliteration accuracy of https://www.pixelssuite.com/chat-translator

## Prerequisites

- Python 3.11 , 3.12 or 3.13
- Google Chrome installed (recommended)

## Installation

```bash
pip install -U pip
pip install playwright openpyxl
playwright install
```

## Running the Tests

```bash
py -3 test_automation.py --excel "Singlish_Test_Cases_50_IT23716278.xlsx" --url "https://www.pixelssuite.com/chat-translator" --wait-ms 5000 --type-delay-ms 80 --slow-mo-ms 200 --save-every 1 --keep-open

## Results

After running, reopen "Singlish_Test_Cases_50_IT23716278.xlsx" — the **Actual output** and **Status** columns will be auto-filled.
