# Password Strength Checker

A simple web-based Password Strength Checker built with Python, Flask, HTML, and CSS. It evaluates a password against basic criteria and displays a strength rating with a percentage indicator.

## Features
- Checks password length (8 or more characters)
- Checks uppercase and lowercase letters
- Checks digits
- Checks selected special characters (`@#$%^&*`)
- Displays a **Weak**, **Medium**, or **Strong** rating
- Shows a percentage score with a visual progress bar

## Tech Stack
- Python
- Flask
- HTML
- CSS
- Regular expressions

## How it works
The checker awards one point for each of its five criteria. It converts the score into a percentage:
- **Weak:** 0–2 criteria
- **Medium:** 3–4 criteria
- **Strong:** 5 criteria

## Run locally
1. Install Python.
2. Open a terminal in the project folder.
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Start the app:
   ```bash
   python app.py
   ```
5. Open the local URL shown in the terminal (usually `http://127.0.0.1:5000`).

## Note
This is an educational password-strength indicator, not a security audit or guarantee that a password is secure. It uses a basic rule-based score and does not check password reuse, leaked passwords, or resistance to advanced cracking techniques.
