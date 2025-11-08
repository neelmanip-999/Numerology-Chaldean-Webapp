🔢✨ Numerology Analyzer — Chaldean Method

🌟 Discover the hidden meaning behind your name and date of birth — powered by ancient numerology and modern technology.

🧠 Project Overview

The Numerology Analyzer is an interactive software that calculates and interprets Chaldean numerology values based on a user’s name and date of birth.
It also visualizes results in a Loshu Grid and provides insights like Birth Number, Destiny Number, Name Number, and Angel Number — all wrapped in an intuitive, dark-themed interface.

👨‍🏫 Faculty Guide

This project has been developed under the guidance of
🎓 Mr. Nikhil Govil Sir, whose continuous mentorship and valuable suggestions shaped our direction and implementation strategy.

👥 Team Members & Roles
👤 Name	🎯 Role(s)	🛠️ Responsibilities
Neelmani Pandey	(Product Owner & Coder)	
▪ Managed product backlog and priorities
▪ Oversaw sprint planning and coordination
▪ Assisted in implementation
Priyanshu Goyal	(Lead Developer & Analyst)	
▪ Designed and developed the entire software architecture
▪ Integrated UI, backend, and numerology modules
▪ Ensured feature completeness, testing, and polish
Prakhar Shahi	(Tester & Analyst)	
▪ Conducted integration testing
▪ Created user stories with acceptance criteria
▪ Assisted in documentation
Namit Jain	(Tester & Analyst)	
▪ Tested all functional modules
▪ Reported bugs and verified fixes
▪ Ensured accuracy of numerology calculations
Durgesh Kumar Gupta	(Tester)	
▪ Executed test cases and UI validation
▪ Ensured consistency across features
Nikhil Chahar	(Tester)	
▪ Performed regression testing
▪ Assisted in final validation

🌀 Our team followed Agile practices emphasizing teamwork, iterative improvements, and adaptability.

💻 Tech Stack
Layer	Technologies
Frontend (UI)	Python (PyQt6)
Backend Logic	Python Modules (core/ folder)
Libraries Used	NumPy, Pandas, Joblib
Optional Integration	Flask (for web deployment)
Version Control	Git & GitHub
IDE	Visual Studio Code
🗂️ Project Structure
NumerologyAnalyzer/
│
├── core/
│   ├── chaldean_mapping.py          # Letter-to-number mapping logic
│   ├── interpretations.py           # Meaning and interpretation of numbers
│   ├── loshu.py                     # Loshu Grid generation
│   ├── numerology_calculations.py   # Core numerology logic (Mulank, Bhagyank, etc.)
│   ├── pdf_report.py                # PDF export functionality
│
├── ui.py                            # GUI Layout & User Interaction
├── main.py                          # Main entry point
├── NumerologyAnalyzer.spec          # Build config for EXE
├── loshu_preview.png                # Preview image for README
├── requirements.txt                 # Dependencies (optional)
└── README.md

⚙️ Features

✅ Chaldean Numerology Analysis — Converts name and DOB into numerological insights
✅ Loshu Grid Visualization — Interactive 3×3 grid showing digit distribution
✅ Multi-Number Insights — Displays Birth Number, Destiny Number, Name Number & Angel Number
✅ PDF Report Export — Save results professionally
✅ Dark-Themed Modern UI — Clean and elegant PyQt interface
✅ Error-Free Input Validation — Smooth user experience

⚡ How to Run the Project
🧩 For Local Development
# 1️⃣ Clone the repository
git clone https://github.com/<your-repo-name>.git
cd NumerologyAnalyzer

# 2️⃣ Run the Python app
python main.py


💡 Make sure you have Python 3.10+ installed.
Optional: Install dependencies manually using
pip install numpy pandas joblib PyQt6

📦 Building Executable (Optional)

You can generate a .exe file using PyInstaller:

pyinstaller --onefile --windowed main.py -n NumerologyAnalyzer


The executable will appear inside the dist/ folder.

🚀 Future Enhancements

🌠 Add Pythagorean Numerology module
🧠 Introduce AI-based personality prediction
📊 Include charts and analytics for better insights
☁️ Deploy as a web version using Flask
🔐 Add user login and saved profiles

🌟 Preview

Here’s how the app looks in action 👇
(Dark-themed UI with Loshu Grid and personalized results)

💫 Vision Statement

“To create a modern numerology tool that combines ancient Chaldean principles with intuitive digital design — helping users gain self-awareness, clarity, and balance through numbers.”

✨ Crafted with precision, creativity, and collaboration by our team.
💙 Every number tells a story — discover yours today!
