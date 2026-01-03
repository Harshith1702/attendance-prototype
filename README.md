# 🌘 Eclipse Attendance App

A web-based QR code attendance management system designed for classrooms and labs.  
The application provides separate teacher and student dashboards, enabling quick attendance marking using QR codes with a clean, modern UI.

This project demonstrates frontend logic, DOM manipulation, state handling, and data export using only HTML, CSS, and JavaScript.

---

## 🚀 Features

### 👩‍🏫 Teacher Dashboard
- Create attendance sessions (subject, section, date)
- Generate QR code for the active session
- View complete attendance table
- Search students by name
- Filter by present / absent status
- Manually mark attendance
- Export attendance data as CSV

### 👨‍🎓 Student Dashboard
- Select student name
- Scan QR (simulated) to mark attendance
- View personal attendance history per session

---

## 🧠 How It Works

1. Teacher creates a session  
2. QR code is generated for that session  
3. Student selects their name and scans QR  
4. Attendance is marked as Present  
5. Teacher reviews and exports records  

⚠️ QR scanning is simulated (no camera access) for simplicity and academic demonstration.

---

## 🛠️ Tech Stack

- HTML5 – Structure  
- CSS3 – Styling & responsive layout  
- JavaScript (Vanilla) – Logic & state management  
- QRCode.js – QR code generation  
- CSV Export (Blob API) – Data download  

No backend. No frameworks. Runs fully in the browser.

---

## 📁 Project Structure
```
Eclipse-Attendance-App/
│
├── index.html # Complete application (HTML, CSS, JS)
└── README.md # Project documentation
```

---

## 📊 Data Handling

- Student list is preloaded
- Attendance stored in JavaScript objects
- Session-based history maintained per student
- Exportable as attendance.csv

---

## ⚠️ Limitations

- No real QR scanning (camera)
- No backend or database
- Data resets on page refresh
- Not production-ready

These limitations are intentional for learning and demonstration.

---

## 🔮 Future Improvements

- Real QR scanning using device camera
- Backend integration (Node.js / Firebase)
- Authentication (Teacher / Student login)
- Cloud database for persistent records
- Mobile-first PWA version

---

## 👤 Author

Harshith  
Computer Science & Engineering Student  
Focused on practical learning through hands-on projects

---

## 📄 License

This project is licensed under the MIT License.  
Free to use and modify for educational purposes.


