# Study Material Management System (MERN + Azure)

A comprehensive **Educational Resource Platform** developed for **Thilini Institute**.  
Built with the **MERN Stack**, this system leverages **Microsoft Azure** services for scalable file storage and advanced AI features, allowing teachers to upload materials and students to access them seamlessly.

<!-- REPLACE WITH YOUR ACTUAL SCREENSHOT -->

---

## 🚀 Features
- ☁️ **Azure Blob Storage**: Secure and scalable cloud storage for lecture notes and PDFs.
- 🎙️ **Azure Speech-to-Text**: AI-powered transcription for accessibility and note generation.
- 🔐 **Role-Based Auth**: Distinct portals for **Teachers** (Uploaders) and **Students** (Viewers).
- 📂 **Material Management**: Easy upload, organization, and download of study resources.
- ⚡ **State Management**: Robust data handling using **React Redux**.
- 🔔 **Real-time Feedback**: User notifications via **React Toast**.

---

## 🛠 Tech Stack

| Layer | Technology |
|--------|-------------|
| **Frontend** | React (Vite), Tailwind CSS, Redux Toolkit, React Toast |
| **Backend** | Node.js, Express.js |
| **Database** | MongoDB |
| **Cloud & AI** | Azure Blob Storage, Azure Speech Services |

---

## 📦 Setup Guide

### 1. Clone Repository
```bash
git clone https://github.com/Gihandev/Study-Material-Management-System-.git
```

### 2. Backend Setup
```bash
npm install
```

### 3. Configure Environment Variables
```bash
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
# Azure Configurations
AZURE_STORAGE_CONNECTION_STRING=your_blob_storage_string
AZURE_SPEECH_KEY=your_speech_api_key
AZURE_SPEECH_REGION=your_azure_region
```
### 4. Run Backend Server
```bash
npm start
```



## 🎥 Demo
Repo Link - https://github.com/Gihandev/Study-Material-Management-System-

---

## ⚠️ Notes & Trade-offs
- Client Project: This system was specifically tailored for the requirements of Thilini Institute.
- Azure Costs: Azure services (Blob/Speech) require an active subscription; ensure quotas are managed.
- Redux: Global state is used to manage user authentication status and material lists efficiently.

## 👨‍💻 Author

Gihan Serasinghe

- Portfolio: https://gihandev.vercel.app/
- GitHub: https://github.com/Gihandev


If you like this project, please give it a ⭐!
