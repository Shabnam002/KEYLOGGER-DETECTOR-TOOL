# KEYLOGGER-DETECTOR-TOOL

# Keylogger Detector Tool – Python GUI App

A simple yet effective Python-based GUI tool to detect potential keyloggers running on your Windows system using process analysis and heuristicS

# Features

1. GUI built with tkinter

2. Signature-based & heuristic keylogger detection

3. Scans common process names for suspicious behavior

4. Displays results in a console-style window

5. One-click Start Detection button

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
![Image](https://github.com/user-attachments/assets/35b8b5df-aa0c-4e7b-8e87-d328e56f63ac)
![Image](https://github.com/user-attachments/assets/3b272348-f349-47d0-835b-66544669ff66)
![Image](https://github.com/user-attachments/assets/68df79eb-8e0d-42af-8d71-fb068c101227)
![Image](https://github.com/user-attachments/assets/cce78b6c-0b67-436e-af0a-c772c96846fa)
![Image](https://github.com/user-attachments/assets/b08d4289-3557-4423-9315-8f62a7e84e12)
![Image](https://github.com/user-attachments/assets/74d2cdb9-45b7-4800-8690-1d04f771aacd)
![Image](https://github.com/user-attachments/assets/485afa17-20ff-4564-9a9b-d9368d134dec)

# License
This project is licensed under the MIT License – feel free to use and modify!
