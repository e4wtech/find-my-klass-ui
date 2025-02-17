# 🎓 Find My Klass

Find My Klass is a platform designed to connect students with educational service providers, offering seamless class discovery, scheduling, and management.

# node v22.13.1
# node v20.14.0

## 🚀 Features
- 🔍 **Class Search** – Easily find classes and training sessions.
- 📅 **Scheduling** – Book and manage class schedules.
- 🏫 **Admin Dashboard** – Manage students, instructors, and class listings.
- 📡 **Real-Time Updates** – Firestore-powered live updates.
- 🔐 **User Authentication** – Google, Facebook, and email login (Firebase Auth).
- 📂 **File Uploads** – Store documents and images (Firebase Storage).
- 📲 **Push Notifications** – Send real-time alerts via Firebase Cloud Messaging (FCM).

---

## 🛠️ Tech Stack
### **Frontend (Ionic Angular)**
- **Framework:** Ionic 7 + Angular 18
- **State Management:** RxJS Observables
- **UI Components:** Ionic UI Kit
- **Hosting:** Firebase Hosting

### **Backend (Node.js / NestJS)**
- **Framework:** NestJS (via Firebase Cloud Functions)
- **Database:** Firestore (NoSQL)
- **Storage:** Firebase Storage (Images, Documents)
- **Admin Dashboard:** Firestore Auto-Generated UI

### **DevOps & CI/CD**
- **Version Control:** GitHub
- **CI/CD:** GitHub Actions → Firebase Hosting
- **Authentication:** Firebase Auth (Google, Facebook, Email)
- **Notifications:** Firebase Cloud Messaging (FCM)

---

## ⚡ Getting Started

### **📦 Prerequisites**
Ensure you have the following installed:
- [Node.js](https://nodejs.org/) (v18 or later)
- [Firebase CLI](https://firebase.google.com/docs/cli) (`npm install -g firebase-tools`)
- [Ionic CLI](https://ionicframework.com/docs/cli) (`npm install -g @ionic/cli`)
- [Git](https://git-scm.com/)

---

### **🏗️ Installation & Setup**
#### **1️⃣ Clone the Repository**

git clone https://github.com/e4wtech/find-my-klass-ui.git
cd find-my-klass-ui


## To manually deploy the frontend:
firebase deploy --only hosting
# To manually deploy backend functions:
firebase deploy --only functions
