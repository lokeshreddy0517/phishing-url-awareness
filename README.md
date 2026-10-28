# EWB Phishing URL Awareness Checker

## Overview
This beginner-friendly Python project checks URL text for common phishing warning signs. It does not open or visit websites.

## Features
- Detects the @ symbol in a URL
- Flags URLs longer than 100 characters
- Detects IP-address-style hostnames
- Flags hostnames with many segments
- Detects punycode-style hostnames
- Warns when HTTP is used

## Requirements
- Python 3.10 or newer
- Visual Studio Code (optional)

## How to Run
1. Install Python.
2. Open a terminal in the project folder.
3. Run:

```bash
python phishing_checker.py
```

4. Enter a sample URL when prompted.

## Testing
Five sample inputs were tested. Results are documented in `tests/test_samples.md`.

## Screenshots
- `Screenshots/sample_run.png`
- `Screenshots/test_results.png`

## Limitations
This tool checks URL text only. It does not visit websites, verify domain ownership, or guarantee that a URL is safe.

## Ethical Use
Use this tool for learning and awareness. Do not enter passwords or sensitive information.

## Implemented Improvements
- **Multiple URL checking:** Users can inspect multiple sample URLs in one session without restarting the program.
- **Quit command:** Users can type `quit` to exit the checker cleanly.

## Future Improvements

- Add stronger URL input validation.
- Provide a clearer final warning summary.
