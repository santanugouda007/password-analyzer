Password Strength Analyzer & Custom Wordlist Generator

Author: Santanu Gouda
Role: Cybersecurity Intern
Project Type: Security Tool (Blue Team + Red Team)

📌 Overview

Weak passwords are still one of the biggest security risks in 2025. This project is a Python-based desktop application designed to:

Analyze password strength using real-world attack models
Detect weak, common, and leaked passwords
Generate strong, secure passwords instantly
Create custom wordlists for ethical penetration testing

It combines usability + security intelligence into one powerful tool.

🚀 Features
🔎 Password Strength Analyzer
Uses zxcvbn algorithm (Dropbox)
Crack time estimation
Shannon entropy calculation
Detects:
Common passwords
Patterns (dates, sequences, repeats)
Leetspeak substitutions
Password policy validation:
Length
Uppercase / lowercase
Digits
Special characters

👉 Output includes:

Strength score (0–4)
Level: Easy / Medium / Hard / Very Hard
Real attack-time estimation
Suggestions to improve password
🔐 Strong Password Generator
Generates highly secure passwords
Ensures complexity requirements
Customizable length
One-click copy to clipboard
🧠 Custom Wordlist Generator (Red Team Feature)
Generates targeted password lists using:
Names
Dates
Pet names
Applies attacker techniques:
Leetspeak (a→@, e→3, etc.)
Year combinations
Capitalization variations
Permutations

👉 Output:

wordlist.txt with thousands of combinations
🛠️ Technologies Used
Technology	Purpose
Python 3	Core development
Tkinter	GUI interface
zxcvbn	Password strength analysis
Regex (re)	Pattern detection
itertools	Wordlist generation
hashlib / secrets	Secure operations
PyInstaller	Convert to executable
📂 Project Structure
Password-Analyzer/
│── main.py
│── wordlist.txt (generated)
│── README.md
│── requirements.txt
⚙️ Installation
1. Clone Repository
git clone https://github.com/yourusername/password-analyzer.git
cd password-analyzer
2. Install Dependencies
pip install zxcvbn
3. Run Application
python main.py
💻 Usage
🔹 Analyze Password
Enter password
Click Analyze
View:
Score
Entropy
Crack time
Suggestions
🔹 Generate Strong Password
Select length
Click Suggest Password
Copy to clipboard
🔹 Generate Wordlist
Enter:
Name / Date / Pet
Select output file
Click Generate Wordlist
🎯 Use Cases
👨‍💼 Organizations – Enforce password policies
🛡️ SOC Analysts – Analyze compromised credentials
🔴 Penetration Testers – Generate targeted wordlists (authorized use only)
🎓 Cybersecurity Training – Demonstrate password weaknesses
⚠️ Disclaimer

This tool is intended ONLY for ethical and educational purposes.

Do NOT use without authorization
Do NOT target real systems illegally
📈 Future Enhancements
Have I Been Pwned (HIBP) integration
AI-based password suggestions
Real-time strength meter
PDF report generation
Multi-language support
📜 License

This project is for educational use. You may modify and use it responsibly.

🙌 Acknowledgment

Built as part of a cybersecurity internship to promote better password hygiene and awareness.
