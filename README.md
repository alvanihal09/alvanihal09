# 🎓 EduPro - AI Powered College Management System

A modern, full-stack College Management System that streamlines academic administration and automates attendance using **AI Face Recognition** and **Time-Based QR Code Verification**.

Built with **React.js**, **Flask**, **SQLite**, and **DeepFace**, EduPro provides a secure, scalable, and user-friendly platform for educational institutions.

---

## ✨ Features

### 👨‍🎓 Student Management
- Student registration and profile management
- Bulk student onboarding via CSV upload
- Department and semester organization
- Student dashboard

### 👨‍🏫 Faculty Management
- Faculty profile management
- Course allocation
- Timetable management
- Attendance monitoring

### 🤖 AI Attendance System
- Face Recognition using DeepFace
- Live webcam verification
- Time-based QR code attendance
- Prevents proxy attendance
- Automatic attendance logging

### 📚 Academic Management
- Course management
- Subject allocation
- Exam scheduling
- Grade management
- Result publication

### 📅 Attendance Analytics
- Daily attendance
- Monthly attendance reports
- Attendance percentage calculation
- Export attendance reports

### 📄 Study Materials
- Upload notes
- Share PDFs
- Assignment distribution
- Learning resources

### 🔐 Authentication & Security
- JWT Authentication
- Role-Based Access Control
- Secure password hashing
- Protected API routes

### 📊 Dashboard
- Student statistics
- Faculty statistics
- Attendance analytics
- Real-time reports
- Interactive charts

---

# 🛠 Tech Stack

## Frontend
- React.js
- Material UI
- React Router
- Axios
- Chart.js

## Backend
- Python
- Flask
- Flask-JWT-Extended
- Flask-CORS

## AI & Computer Vision
- DeepFace
- OpenCV
- NumPy

## Database
- SQLite3

## Authentication
- JWT Tokens

---

# 📂 Project Structure

```
EduPro/
│
├── backend/
│   ├── app.py
│   ├── face_attendance.py
│   ├── routes/
│   ├── database/
│   ├── models/
│   ├── uploads/
│   └── requirements.txt
│
├── frontend/
│   ├── public/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── context/
│   │   ├── services/
│   │   └── App.js
│   └── package.json
│
└── README.md
```

---

# ⚙ Installation

## Clone the repository

```bash
git clone https://github.com/yourusername/EduPro.git

cd EduPro
```

---

## Backend Setup

Create a virtual environment

```bash
python -m venv venv
```

Activate it

### Windows

```bash
venv\Scripts\activate
```

### Linux/Mac

```bash
source venv/bin/activate
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run Flask

```bash
python app.py
```

Backend runs on

```
http://localhost:5050
```

---

## Frontend Setup

Navigate to frontend

```bash
cd frontend
```

Install packages

```bash
npm install
```

Start React

```bash
npm start
```

Frontend runs on

```
http://localhost:3000
```

---

# 📸 AI Attendance Workflow

1. Faculty generates a QR Code.
2. QR code is displayed in the classroom.
3. Student scans the QR code.
4. Webcam opens automatically.
5. DeepFace verifies the student's face.
6. Attendance is recorded only after successful face verification.
7. Attendance is stored securely in the database.

---

# 📷 Screenshots

## Login Page

(Add Screenshot Here)

---

## Dashboard

(Add Screenshot Here)

---

## Attendance Page

(Add Screenshot Here)

---

## QR Attendance

(Add Screenshot Here)

---

## Face Recognition

(Add Screenshot Here)

---

# 🔒 Security Features

- JWT Authentication
- Role-based Authorization
- Password Encryption
- Protected API Routes
- QR Session Expiry
- Live Face Verification
- Duplicate Attendance Prevention

---

# 🚀 Future Enhancements

- Email Notifications
- SMS Alerts
- Cloud Database Support
- Multi-College Support
- AI Performance Analytics
- Mobile Application
- Docker Deployment
- CI/CD Pipeline

---

# 👨‍💻 Author

**Nihal Alva**

BCA Student | AI & Full Stack Developer

**Skills**

- Python
- Flask
- React.js
- JavaScript
- Material UI
- SQLite
- REST APIs
- JWT Authentication
- DeepFace
- OpenCV
- Git
- GitHub

---

# ⭐ Support

If you found this project useful, consider giving it a ⭐ on GitHub.

---

# 📜 License

This project is licensed under the MIT License.
<!--
**alvanihal09/alvanihal09** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
