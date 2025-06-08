Flask Web Application – Aditya Jaiswal

This is a Flask-based web application developed by Aditya Jaiswal. It supports basic web functionality using HTML templates and integrates with an SQLite database.

🚀 Features

Dynamic HTML templates (index, about, update)

SQLite database integration

Deployed with Heroku (via Procfile)

Modular structure for scalable development


📁 Project Structure

Aditya-Jaiswal-GIT-main/
├── app.py                # Main Flask app
├── requirment.txt        # Python dependencies
├── Procfile              # For Heroku deployment
├── instance/
│   └── aditya.db         # SQLite database
├── templates/            # HTML pages
│   ├── base.html
│   ├── index.html
│   ├── about.html
│   └── update.html

💻 Installation

1. Clone the repository

git clone https://github.com/<your-username>/Aditya-Jaiswal-GIT.git
cd Aditya-Jaiswal-GIT


2. Create a virtual environment and activate it

python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate


3. Install dependencies

pip install -r requirment.txt


4. Run the application

python app.py


5. Visit in browser

http://127.0.0.1:5000/



🌐 Deployment

This app is ready for deployment on Heroku. Make sure to:

Add Procfile

Install gunicorn

Push to a GitHub repository and link to Heroku


📄 License

This project is open-source and available under the MIT License.


---

Note: You may want to rename requirment.txt to requirements.txt to follow standard conventions.

