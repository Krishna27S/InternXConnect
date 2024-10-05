FILE DIRECTORY 
project-root/
│
├── config.js                  # MongoDB user schema (User model)
│
├── index.js                   # Main Express application file (formerly app.js)
│
├── public/                    # Static assets (like CSS, images, JavaScript)
│   ├── css/
│   ├── js/
│   └── images/
│
├── views/                     # EJS templates
│   ├── login.ejs
│   ├── signup.ejs
│   ├── templates.ejs
│   ├── newTemplate.ejs
│   └── editTemplate.ejs
│
├── package.json               # Project dependencies and scripts
│
└── package-lock.json          # Automatically generated lock file

Here's a structured `README.md` file for your project. This file includes information about your project, the tech stack, required packages, and instructions on how to run the server.

```markdown
# InternXConnect

InternXConnect is a web application that allows users to create and manage templates, with user authentication and session management. This application is designed for managing templates easily and effectively.

## Table of Contents

- [Tech Stack](#tech-stack)
- [Features](#features)
- [Installation](#installation)
- [Required Packages](#required-packages)
- [How to Run the Server](#how-to-run-the-server)
- [License](#license)

## Tech Stack

- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Templating**: EJS (Embedded JavaScript)
- **Authentication**: bcrypt for password hashing, express-session for session management

## Features

- User signup and login
- Template creation, editing, and deletion (Admin only)
- User role management (Applicant/Employer)
- Secure password storage and authentication
- Session management for logged-in users

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Krishna27S/InternXConnect.git
   ```

2. Navigate to the project directory:
   ```bash
   cd InternXConnect
   ```

3. Install the required packages:
   ```bash
   npm install
   ```

4. Ensure you have MongoDB installed and running on your machine.

## Required Packages

To run this project, you need to install the following packages:
- `express`
- `mongoose`
- `bcrypt`
- `express-session`
- `ejs`

You can install all the required packages by running:
```bash
npm install express mongoose bcrypt express-session ejs
```

## How to Run the Server

1. Start the MongoDB server if it's not running:
   ```bash
   mongod
   ```

2. Start the Express server:
   ```bash
   node index.js
   ```

3. Open your browser and navigate to `http://localhost:5000` to access the application.



### Instructions for Use:
- Replace `index.js` with the actual filename of your main server file if it’s different.
- Make sure to adjust the license section according to your project's license type.

You can create a file named `README.md` in the root of your project directory and copy the content above into it. This will help other developers understand your project better and how to contribute to it.



![image](https://github.com/user-attachments/assets/bc1bdba9-ae3a-4036-a2f9-946b72bdb3ba)

![image](https://github.com/user-attachments/assets/be370910-83cc-413e-8200-cb638bd82a37)

![image](https://github.com/user-attachments/assets/6d52c364-0b73-48ed-9436-a0b079a78b16)

![image](https://github.com/user-attachments/assets/6f26728b-e3eb-4d9b-9abc-674bfdcf2d87)



