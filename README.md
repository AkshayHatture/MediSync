# 🩺 MediSync – Smart Medical Records & Prescription Management

**MediSync** is a modern full-stack healthcare application designed to help patients securely manage and access their medical data. It provides an intuitive interface for storing prescriptions (PDF, JPEG, JPG), tracking injection and medicine records, and enabling seamless access to medical history from anywhere.

---

## ✨ Features (Planned)

- 🔐 **User Authentication** – Secure login and registration
- 📂 **Prescription Upload** – Upload and store medical documents (PDF, JPG, JPEG)
- 👨‍⚕️ **Medical History Tracking** – Log and view past injections and medications
- 🧾 **In-App Viewing** – View documents directly in the browser
- ☁️ **Cloud Storage** – Firebase Storage for safe and reliable file hosting
- 📱 **Responsive Design** – Accessible across devices

---

## 🧰 Tech Stack

- **Frontend**: React.js, Tailwind CSS
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **File Storage**: Firebase Storage
- **Authentication**: JWT (planned)

---

## 🚀 Getting Started

> ⚠️ *This project is currently under development. The instructions below are placeholders and will be updated as the app progresses.*

### Prerequisites

- Node.js and npm
- Firebase Project & MongoDB Atlas setup

### Installation

1. Clone the repository

   ```bash
   git clone https://github.com/akshayhatture/MediSync.git
   cd medisync
   ```

2. Install dependencies

   ```bash
   npm install
   ```

3. Configure environment variables

   Create a `.env` file with:

   ```env
   MONGO_URI=your_mongodb_connection_string
   FIREBASE_API_KEY=your_firebase_key
   JWT_SECRET=your_jwt_secret
   ```

4. Start the server

   ```bash
   npm start
   ```

---

## 📁 Project Structure (Planned)

```
medisync/
├── backend/
│   ├── models/
│   ├── routes/
│   └── controllers/
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   └── App.js
└── README.md
```

---

## 📌 Roadmap

- [ ] Build authentication system
- [ ] Integrate Firebase Storage
- [ ] Develop prescription upload & view module
- [ ] Add prescription/medicine tracking
- [ ] Polish UI with responsive design
- [ ] Deploy to Vercel & Render

---

## 🛠️ Contributing

Contributions are welcome! Please open an issue or submit a pull request for improvements or fixes.

---

## 📬 Contact

Have suggestions or feedback? Reach out:  
📧 akshayhatture11@gmail.com
