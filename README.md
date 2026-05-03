# IT23836754-Playwright-Automation-Testing

## Overview

This repository contains a Python-based Playwright automation script that reads Singlish test inputs from an Excel workbook, sends them to the chat translator UI, and writes the translated output and pass/fail result back into the workbook.

## Prerequisites

- Python 3.10 or newer
- Google Chrome or Microsoft Edge
- Internet access for the first Playwright browser install

## Install Dependencies

From the repository root, run:

```powershell
python -m pip install --upgrade pip
python -m pip install -r requirements.txt
python -m playwright install chromium
```

## Run the Automation

The script uses the bundled Excel file by default. To run it:

```powershell
python test_automation.py
```

## Useful Options

You can override the defaults if needed:

```powershell
python test_automation.py --excel "Assignment 1 - Test cases It23836754.xlsx" --headless
```

Common flags:

- `--url` to change the target frontend URL
- `--headless` to run without opening the browser window
- `--output` to write results to a different workbook
- `--save-every` to periodically save progress while the script runs

## Git Repository Link

The repository link is also available in [git_repository_link.txt](git_repository_link.txt).