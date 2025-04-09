# KEYLOGGER-DETECTOR-TOOL

# Keylogger Detector Tool – Python GUI App

A simple yet effective Python-based GUI tool to detect potential keyloggers running on your Windows system using process analysis and heuristicS

# Features

✅ GUI built with tkinter

🧠 Signature-based & heuristic keylogger detection

🕵️ Scans common process names for suspicious behavior

🔎 Displays results in a console-style window

🔘 One-click Start Detection button

# How to Run 

# Clone this repo or download the .py file:
git clone https://github.com/your-username/keylogger-detector.git
cd keylogger-detector

# Install required Python packages:
pip install psutil

# Run the app:
python keylogger_detector.py

# How to Convert to .exe 
Use PyInstaller:
pip install pyinstaller
pyinstaller --noconsole --onefile keylogger_detector.py
Your .exe will appear in the dist/ folder.

# Project Structure
keylogger-detector/
-keylogger_detector.py       # Main Python GUI script
-README.md                   # Project description
-dist/                       # Contains .exe (after PyInstaller)
-build/                      # Auto-generated (PyInstaller)
-Keylogger_detector.spec     # Auto-generated (PyInstaller)

# Limitations
1. Basic detection only (heuristics & known patterns)

2. No real-time monitoring (manual scan)

3. Doesn't terminate or quarantine detected processes

4. Windows-only (uses Windows-specific features)

# OUTPUT



# License
This project is licensed under the MIT License – feel free to use and modify!
