📱 QR-Based Smart Campus Attendance and Real-Time Parent Notification System
🧩 Introduction

The QR-Based Smart Campus Attendance and Real-Time Parent Notification System automates student attendance monitoring using QR codes. Manual attendance processes are often time-consuming, error-prone, and inefficient for large classes. This system enables teachers to record attendance effortlessly while automatically notifying parents about absences or tardiness via SMS or email.
By combining QR code technology, Laravel, and React.js, it ensures efficient tracking, secure data storage, and real-time communication between schools and parents.

📚 Table of Contents

Problem Statement

Objectives

Scope and Limitations

Target Users / Beneficiaries

System Features

Technologies and Tools

🧠 Problem Statement

Manual attendance checking consumes valuable class time and is prone to human error. Teachers must manually record attendance, while parents often remain unaware of their child’s daily attendance status. This system addresses these challenges by automating attendance tracking through QR code scanning and providing real-time notifications to parents and administrators.

🎯 Objectives
General Objective

To automate student attendance monitoring and provide real-time notifications to parents and school administrators.

Specific Objectives

Develop a QR code–based attendance tracking system that can be scanned using any device camera.

Send SMS/email notifications to parents when students are absent or late.

Generate automated attendance reports accessible to teachers and administrators.

Maintain a secure database for reliable record storage and retrieval.

📋 Scope and Limitations
Scope

QR code–based attendance scanning for classrooms.

Notifications sent through SMS/email APIs.

Automated attendance reports for teachers and administrators.

Limitations

Focused solely on attendance tracking (no academic grading integration).

Requires internet connectivity for API-based notifications.

QR scanning performance may vary based on camera quality and lighting conditions.

👥 Target Users / Beneficiaries

Teachers: For quick and accurate attendance tracking.

Students: For transparent attendance records.

Parents: For real-time attendance updates.

School Administrators: For efficient monitoring and reporting.

⚙️ System Features

✅ QR Code Generation and Scanning

📧 Real-Time Email/SMS Notifications

📊 Automated Attendance Reports

🔒 Secure Database for Record Storage

🧾 Dashboard for Teachers and Administrators

💻 Technologies and Tools
Database:	MySQL
Backend:	Laravel (PHP)
Frontend:	React.js
Email Integration:	EmailJS
Calendar Management:	Google Calendar API
QR Code Generation:	qrcode.react
QR Code Scanning:	react-qr-reader
