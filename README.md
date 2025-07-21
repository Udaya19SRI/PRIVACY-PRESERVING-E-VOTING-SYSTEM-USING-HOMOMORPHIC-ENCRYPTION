# 🗳️ Privacy-Preserving E-Voting System using Homomorphic Encryption & Facial Recognition

> A secure, biometric-based electronic voting system using Paillier Homomorphic Encryption and OpenCV facial authentication.

![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python)
![Flask](https://img.shields.io/badge/Flask-Framework-green)
![License](https://img.shields.io/badge/License-MIT-lightgrey)
![Status](https://img.shields.io/badge/Project-Complete-brightgreen)

## 📌 Abstract

This project proposes a secure, privacy-preserving e-voting system using:
- **Homomorphic encryption** (Paillier) to protect vote confidentiality.
- **Facial recognition** (OpenCV LBPH) for voter authentication.

Votes are encrypted at submission, stored securely, and only decrypted in aggregated form by an authorized admin. The system is suitable for small elections in controlled environments like academic institutions or organizations.

---

## 🔐 Key Features

- 🔐 **Paillier Homomorphic Encryption** for vote privacy  
- 🧑‍🦰 **Facial Recognition Authentication** using OpenCV (LBPH)
- 🧑‍💼 **Admin Portal** for result decryption and viewing
- 🗳️ **Vote Once Policy** — each voter can vote only once
- 🧪 Tested with **Unit, Integration, Security** and **Spoofing scenarios**
- 📊 **Encrypted Database** to store sensitive data securely

---

## 🧑‍💻 Technologies Used

| Layer        | Tech Stack                             |
|--------------|----------------------------------------|
| Frontend     | HTML5, CSS3, JavaScript                |
| Backend      | Python 3.x, Flask                      |
| Database     | SQLite                                 |
| Facial Auth  | OpenCV, LBPH algorithm                 |
| Encryption   | Paillier (PyCryptodome implementation) |
| Security     | SHA256 Hashing for admin credentials   |

---

## 🧰 Project Structure
e-voting-homomorphic/
│
├── app/                  # Core backend logic (Flask, encryption, auth)
├── templates/            # HTML templates (Jinja2)
├── static/               # CSS and JS for UI
├── trainer/              # Face training logic and data
├── database/             # SQLite DB (or DB scripts)
├── tests/                # Unit and integration tests
├── app.py                # Main Flask application
├── requirements.txt      # Project dependencies
├── README.md             # Project documentation (this file)
├── LICENSE               # MIT or other license
└── .gitignore

---

## 🚀 Installation & Running Locally

### 1. Clone the repository
```bash
git clone https://github.com/YourUsername/e-voting-homomorphic.git
cd e-voting-homomorphic

### 2. Install dependencies
pip install -r requirements.txt

### 3. Train the facial recognition model
python trainer/trainer.py

### 4. Start the Flask app
python app.py
Visit the app at: http://127.0.0.1:5000

🔎 Sample Screenshots
Facial Login
Voting Screen
Admin Portal

📚 Project Report

The full project documentation with diagrams, methodology, encryption flow, test cases, and future scope is available in the /docs folder or click here to view the PDF.

✅ Future Enhancements
	•	🔐 Add multi-factor authentication (OTP + Biometrics)
	•	🌐 Deploy to cloud with HTTPS and scalable DB
	•	🤖 Upgrade to deep learning-based face recognition (FaceNet)
	•	🔗 Add blockchain-based vote transparency
	•	📱 Develop a mobile voting interface


🧑‍🏫 Contributors
	•	B. Jahnavi
	•	M. Shashi Preetham
	•	P. Udaya Sri
	•	B. Pravarshan

📄 License

This project is licensed under the MIT License - see the LICENSE file for details.



🙏 Acknowledgements
	•	VNR VJIET - Department of CSE (CyS, DS) and AI&DS
	•	Guide: Mr. N. Sudheer
	•	OpenCV, PyCryptodome, Flask, Python

---

Would you like a `.zip` of the entire folder structure including a sample `app.py`, `trainer.py`, and HTML files to get started?
