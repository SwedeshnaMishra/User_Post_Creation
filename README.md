# 📝 User Post Creation Web App

A simple web application that allows users to register, log in, and create, edit, and view posts. Built with Node.js, Express, MongoDB, and EJS.

---

## 🚀 Features

- 👤 User Registration and Authentication
- 🔐 Secure Login with Session Handling
- 📝 Create, Edit, and View Posts
- 📄 Dynamic Templates with EJS
- 🗃 MongoDB-backed Data Storage
- ✨ Minimalist UI for fast interaction

---

## 📁 Folder Structure

```
User Post Creation/
│
├── models/
│ ├── post.js # Mongoose schema for posts
│ └── user.js # Mongoose schema for users
│
├── views/
│ ├── index.ejs # Homepage displaying posts
│ ├── login.ejs # Login page
│ ├── profile.ejs # User profile and post management
│ └── edit.ejs # Edit post page
│
├── app.js # Express server & route handlers
├── package.json # Project dependencies
├── package-lock.json
└── README.md # Project documentation
```

---

## 🛠️ Tech Stack

- **Backend**: Node.js, Express
- **Templating**: EJS
- **Database**: MongoDB with Mongoose
- **Authentication**: Express-Session / Passport.js (based on your implementation)

---

## 🧪 Installation & Setup

### 1. Clone the repository

   ```bash
   git clone https://github.com/SwedeshnaMishra/User_Post_Creation.git
   cd User_Post_Creation
   ```

### 2. Install Dependencies

```bash
npm install
```

### 3. Set up environment variables
Create a .env file (if used) for your MongoDB URI, session secret, etc.

### 3. Run the application

```bash
node app.js
```

---

## How to Use 
- Register/Login through the login page.
- Create a new post via your profile/dashboard.
- View all posts on the homepage.
- Edit or delete posts from the profile page

---

## For Contributing
If you want to contribute to this project, please follow these steps:
- `Fork` the repository.
- Create a new branch `(git checkout -b feature/your-feature-name)`.
- Make your changes and commit them `(git commit -m 'Add some feature')`.
- Push to the branch `(git push origin feature/your-feature-name)`.
- Open a pull request.

---

## Project Maintainer
**Github:** [Swedeshna Mishra](https://github.com/SwedeshnaMishra)
