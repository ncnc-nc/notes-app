# Notes App 

A full-stack web application built with **React, Node.js, Express, and MongoDB** that allows users to register, log in, and manage notes with features like pinning and favoriting.

## Features
- User authentication (Register/Login with JWT)
- Create, Read, Update, Delete (CRUD) notes
- Pin/unpin notes 
- Mark/unmark notes as favorite 
- Protected routes with conditional rendering
- Modern card-based UI with responsive design

---

## Tech Stack
- **Frontend**: React, React Router, Axios, CSS
- **Backend**: Node.js, Express.js
- **Database**: MongoDB (Mongoose ODM)
- **Authentication**: JWT + bcrypt

---

##  Project Structure
notes-app/
├── backend/
│   ├── config/
│   │   └── db.js             
│   ├── controllers/
│   │   ├── userController.js  
│   │   └── noteController.js 
│   ├── middleware/
│   │   └── authMiddleware.js  
│   ├── models/
│   │   ├── User.js           
│   │   └── Note.js           
│   ├── routes/
│   │   ├── userRoutes.js      
│   │   └── noteRoutes.js      
│   ├── server.js              
│   └── package.json           
│
├── frontend/
│   ├── public/
│   │   └── index.html         
│   ├── src/
│   │   ├── components/
│   │   │   ├── Navbar.js       
│   │   │   ├── Register.js    
│   │   │   ├── Login.js       
│   │   │   ├── NotesList.js   
│   │   │   ├── NoteItem.js    
│   │   │   └── NoteForm.js    
│   │   ├── services/
│   │   │   └── api.js         
│   │   ├── App.js            
│   │   ├── App.css            
│   │   └── index.js           
│   └── package.json          
│
├── .env                       
├── README.md                  
└── package.json               
