# 🔐 Phishing URL Detector

A beginner-friendly cybersecurity project built with Python that analyzes URLs and identifies suspicious characteristics commonly associated with phishing attempts.

## 📌 Features

- 🔎 URL parsing and analysis
- 🌐 IP address detection
- 🔒 HTTPS verification
- ⚠️ Suspicious keyword detection
- 📏 Unusually long URL detection
- 🔣 @ symbol detection
- 🌳 Domain/subdomain structure analysis
- 📊 Risk scoring system
- 🖥️ Graphical User Interface (GUI)
- 📋 Security report generation

## 🛠️ Technologies Used

- Python
- Tkinter
- Regular Expressions
- urllib.parse

## ⚙️ How It Works

The user enters a URL into the application.

The detector analyzes different characteristics of the URL and assigns risk points based on suspicious indicators.

The final result contains:

- Risk Score
- Risk Level
- Detected Warning Reasons

### Risk Levels

| Score | Risk Level |
|------:|------------|
| 0–2 | LOW |
| 3–5 | MEDIUM |
| 6+ | HIGH |

## 🚀 How to Run

1. Make sure Python is installed.
2. Download or clone this repository.
3. Open the project folder in VS Code.
4. Run:

```bash
python phishing_detector.py