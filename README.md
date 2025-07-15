# TabulaX

TabulaX is a [brief one-liner about your project]. This project is aimed at [goal/purpose of the project], built with [technologies or libraries used].

---

## 🚀 Features

📊 LLM-powered Table Classification
Automatically detects whether a transformation is string-based, numerical, algorithmic, or general.

🧠 Prompt-Based or Example-Based Code Generation
Generates Python functions using Google Gemini based on examples or user instructions.

⚡ Safe Code Execution & Transformation
Dynamically applies generated functions to real data using a secure, restricted execution environment.

📈 Transformation Health Reporting
Reports on transformation success rate, value changes, null handling, and sample previews.

🗂️ CSV/JSON Upload Support via Flask
User can upload data directly through a web interface and receive transformed outputs.

---

## 📂 Project Structure

TabulaX/
├── main.py                          # Main testing script
├── transformation_service.py       # LLM logic and transformation engine
├── flask_app/                      # Flask-based frontend (optional)
├── examples/                       # Sample input tables
├── utils/                          # Helper functions
└── requirements.txt

## 🛠️ Installation


git clone https://github.com/Nandhan0710/TabulaX.git
cd TabulaX
pip install -r requirements.txt
python main.py
