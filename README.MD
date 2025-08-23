======================================================
 🚀 PursueX - Web Based Reconnaissance Toolkit
======================================================

PursueX is a lightweight reconnaissance toolkit built with
Python and Flask. It provides a simple web interface to
run scans and view results at:

   👉 http://localhost:5000

------------------------------------------------------
📥 Installation
------------------------------------------------------

1. Download the latest pursuex.zip and unzip it:
   git clone https://github.com/dipeshjatt2/pursuex
   cd pursuex 
   unzip pursuex.zip
   cd pursuex

2. (Optional) Create a virtual environment:
   python3 -m venv venv
   source venv/bin/activate      # Linux / Mac
   venv\Scripts\activate         # Windows

3. Install required dependencies:
   pip install -r requirements.txt
### for termux 
run bash up.sh
------------------------------------------------------
▶️ Usage
------------------------------------------------------

1. Run the Flask app:
   python app.py

2. Open your browser and go to:
   http://localhost:5000

------------------------------------------------------
⚡ Features
------------------------------------------------------

- Subdomain enumeration
- Port scanning
- Web dashboard with live progress
- Export scan results

------------------------------------------------------
🛠 Development (Optional)
------------------------------------------------------

Run in development mode with auto reload:

   export FLASK_APP=app.py
   export FLASK_ENV=development
   flask run

------------------------------------------------------
📜 License
------------------------------------------------------

This project is licensed under the MIT License.
Contributions are welcome ✨
