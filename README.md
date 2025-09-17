# School Management System 📚🏫

The School Management System (SMS) is a full-stack, web-based application built using the **MERN stack (MongoDB, Express.js, React.js, Node.js)**. It helps schools manage students, teachers, classes, subjects, attendance, exams, and notices efficiently. With a clean interface and role-based access, SMS simplifies day-to-day school operations for admins, teachers, and students. 🚀

---

## Key Features ✨

### Admin 👨‍💼
- Manage students, teachers, classes, and subjects.  
- Track and update student attendance and exam marks.  
- Post notices for students and teachers.  
- Role-based access ensures secure management of the system.  

### Teacher 👩‍🏫
- Access assigned classes and subjects.  
- Update student attendance and exam marks.  
- View student profiles and notices.  

### Student 🎓
- View personal information, attendance, and exam marks.  
- Access notices from admin or teachers.  

### Profile & Security 🔒
- Update personal info and password.  
- Passwords are hashed securely using **bcryptjs**.  
- JWT authentication ensures safe API access.  

---

## Technologies Used 🖥️⚙️
- **Frontend:** React.js, Redux, Material UI  
- **Backend:** Node.js, Express.js  
- **Database:** MongoDB (Atlas or local)  
- **Authentication & Security:** JWT, bcryptjs  
- **Deployment:** Render (Backend), Vercel (Frontend)  

---

## Live Demo 🌐
- **Frontend:** [https://school-management-system-six-khaki.vercel.app/](https://school-management-system-six-khaki.vercel.app/)  
- **Backend:** (Render URL once deployed)

---

## Installation 💻

### Backend
1. Navigate to the backend folder:
```bash
cd backend
```
2. Install dependencies:
```bash
npm install
```
3. Create a .env file in the backend folder with the following:
MONGO_URL=<Your MongoDB Atlas URI>
PORT=5000
4. Start the backend server:
```bash
npm start
```
### Frontend
1. Navigate to the frontend folder:
```bash
cd frontend
```
2. Install dependencies:
```bash
npm install
```
3. Create a .env file in the frontend folder with the following:
REACT_APP_BASE_URL=<Your backend URL>
4. Start the frontend server:
```bash
npm start
```
