# Multi-Page React Application with Routing

Author: Ashfaaq Feroz Muhammad  
Assignment: Entri Assignment (11)  
Purpose: Educational project to practice React Router and multi-page layout.

## Features
- Home, About, Users list, and User Detail pages using React Router.
- Persistent navigation bar with active link styling.
- Mock user data with parameterized routes for user details.

## Folder structure
```
root/
├─ README.md
└─ dev/
   ├─ index.html
   ├─ package.json
   ├─ vite.config.js
   └─ src/
      ├─ App.jsx
      ├─ main.jsx
      ├─ styles.css
      ├─ components/
      │  └─ Navbar.jsx
      ├─ data/
      │  └─ users.js
      └─ pages/
         ├─ About.jsx
         ├─ Home.jsx
         ├─ UserDetail.jsx
         └─ Users.jsx
```

## How to run
1) Open terminal in the root folder.
2) Go to project folder: `cd dev`
3) Install dependencies: `npm install`
4) Start dev server: `npm run dev`
5) Open the URL shown in the terminal.

## Notes
- If port 5173 is blocked, run: `npm run dev -- --host 127.0.0.1 --port 5174`
- This project is for educational purpose.
