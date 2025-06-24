# Password-Protected Secrets Page 🔒

This is a simple Node.js and Express application that serves a public HTML page and checks for a password using a POST request. If the password is correct, it serves a secret HTML page.

## 🚀 Features

- Serves a static homepage (`index.html`)
- Validates user input via form submission
- Shows a secret page only if the correct password is provided

## 📁 Project Structure

project-folder/
│
├── public/
│ ├── index.html # Public home page with a password form
│ └── secret.html # Hidden page shown on correct password
│
├── index.js # Express server file 
|── package.json
|__package-lock.json


## 🛠️ Installation & Usage

1. Clone the repository or download the files.
2. Run the following commands in your terminal:

bash
npm install express body-parser
node server.js

