# 🔐 SignUp-Login_form    

A simple user authentication interface built with **React.js**, demonstrating basic **Sign Up** and **Login** functionalities using local state and localStorage.


## 🚀 Features

- Simple Sign Up form (with username, email, and password)
- Login validation
- LocalStorage-based user data (No backend)
- Basic routing with `react-router-dom`

## 🛠️ Installation

1. **Clone the repository**

```bash
git clone https://github.com/SwathiPriya37/signup-login-react.git
cd signup-login-react
```
2. Install dependencies

```bash
npm install
```
3. Start the development server

```bash
npm start
```
Visit http://localhost:3000 in your browser.

## 🔧 Technologies Used
1. ReactJS
2. React Router DOM
3. LocalStorage
4. CSS

## 🧠 How It Works
- On Sign Up, user details are saved in browser's localStorage.
- On Login, credentials are verified from localStorage.
- If authenticated, a welcome message is shown.
- No database or server is involved in this basic demo.

## 📌 Note
This is just for educational purposes. Do not use this method for production apps, as localStorage is not secure for storing sensitive data.
