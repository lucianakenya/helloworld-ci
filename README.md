# 🚀 Hello CI/CD
This is a beginner-friendly project that demonstrates how to set up a CI/CD pipeline using GitHub Actions — no cloud servers required. It uses a simple Flask app, GitHub Actions for automation, and optional Docker support.
---
## 🧰 Tech Stack
- Python (Flask)
- Git & GitHub
- GitHub Actions
- PyTest
- Git CMD + Notepad (Windows)
---
## 📦 Features
- Simple Flask web app
- Automated testing with PyTest
- CI pipeline triggered on every push
- Dockerized application (optional)
---
## 🚀 How to Run Locally
```bash
pip install -r requirements.txt
python app.py
Visit: http://localhost:5000
🔁 CI/CD Pipeline
Every push to the master branch triggers:
Dependency installation
Test execution with PyTest
You can view the pipeline in the Actions tab of your GitHub repository.
🧪 Testing
pip install pytest
pytest
🐳 Docker (Optional)
To build and run the app in a Docker container:
docker build -t hello-ci .
docker run -p 5000:5000 hello-ci
📁 Project Structure
hello-ci/
├── app.py
├── requirements.txt
├── test_app.py
├── README.md
└── .github/
    └── workflows/
        └── python-app.yml
📝 Author
Created by Lucy Nyambura
GitHub: https://github.com/lucianakenya