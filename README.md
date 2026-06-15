# 🏙️ Smart Complaint Management System

A web-based Smart Complaint Management System developed to improve communication between citizens and local authorities. The system allows citizens to report civic issues, enables administrators to assign tasks to workers, and provides real-time status tracking until the issue is resolved.

## 🚀 Features

### 👨‍💼 Citizen Panel
- Submit complaints regarding civic issues.
- Upload images as proof.
- Enter area and complaint description.
- Complaint automatically stored in Firebase.

### 🛠️ Admin Panel
- View all pending complaints.
- Assign complaints to workers.
- Send task details directly via email.
- Track complaint progress.

### 👷 Worker Panel
- View assigned tasks.
- Upload work completion proof.
- Mark tasks as completed.
- Status automatically updated in the database.

### 📊 Complaint Tracking
- Pending Requests
- Assigned Requests
- Completed Requests
- Proof Verification

---

## 🏗️ Tech Stack

### Frontend
- Next.js
- React.js
- CSS

### Backend
- Next.js API Routes
- Node.js

### Database
- Firebase Firestore

### Email Service
- Nodemailer
- Gmail SMTP

---

## 📂 Project Structure

```bash
src/
│
├── app/
│   ├── citizen/
│   ├── admin/
│   │   ├── pending/
│   │   └── assigned/
│   ├── worker/
│   └── api/
│       ├── assign/
│       ├── complaints/
│       └── complete/
│
├── lib/
│   └── firebase.js
│
└── app/globals.css
```

---

## 🔄 Workflow

1. Citizen submits complaint.
2. Complaint appears in Admin Pending Requests.
3. Admin assigns task to worker.
4. Worker receives email notification.
5. Worker uploads proof and marks task as completed.
6. Admin verifies completion through Assigned Tasks section.

---

## 📧 Email Notification System

When an admin assigns a task:

- Worker receives an email notification.
- Email contains:
  - Task details
  - Instructions
  - Assignment information

Powered by:
- Nodemailer
- Gmail SMTP

---

## 🔥 Firebase Integration

Used for:

- Complaint Storage
- Task Assignment
- Status Tracking
- Worker Proof Storage

---

## 🌟 Future Enhancements

- Authentication & Role-Based Login
- SMS Notifications
- Live Complaint Tracking
- Analytics Dashboard
- GIS / Smart City Integration
- Mobile Application
- Multi-language Support

---

## 🎯 Real-World Applications

The system can be extended to handle:

- Waste Management
- Road Damage Reporting
- Street Light Failures
- Water Leakage Complaints
- Drainage Issues
- Public Sanitation Issues
- Illegal Dumping Reports
- Public Infrastructure Maintenance

---

## 👨‍💻 Developed By

**Chaitanya Kapure**

B.Tech Information Technology

Smart City & Civic Technology Enthusiast

---

## 📜 License

This project is developed for educational, research, and smart governance purposes.
