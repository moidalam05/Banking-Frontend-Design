# 🏦 Banking Frontend Design  

A **modern landing page** for a banking website, built using **HTML, CSS, JavaScript, and Tailwind CSS**.  
Designed to deliver a clean, professional look with responsive and user-friendly interface elements.  

---

## ✨ Features  
- Modern and professional **banking UI**  
- Responsive design for desktop and mobile  
- Interactive elements like buttons, forms, and service highlights  
- Sections for services, testimonials, and call-to-action  

---

## 🛠️ Tech Stack  
- **HTML5**  
- **CSS3**  
- **Tailwind CSS**  
- **JavaScript (ES6)**  

---

## 📂 Project Structure  
banking-frontend/
│── index.html # Main landing page
│── style.css # Custom styling
│── script.js # Optional interactivity
│── assets/ # Images, icons, and graphics


---

## 🚀 How It Works  
1. Open `index.html` in any web browser.  
2. Navigate through sections like Home, Services, and Contact.  
3. Interactive elements respond with smooth animations and hover effects.  

---

## 🎯 Purpose  
This project was created to **practice modern front-end development** using Tailwind CSS, focusing on clean UI design and responsive landing pages for banking applications.  

---
✨ *A professional, modern, and responsive banking landing page UI.*  

# Tailwind Setup

## commands

```commands
npm init -y
npm i -D tailwindcss
npx tailwindcss init
```

## Add configuration in config.js files

```javascript
/** @type {import('tailwindcss').Config} */
module.exports = {
  content: ["./*.{html,js}"],
  theme: {
    extend: {},
  },
  plugins: [],
}
```

## Add the Tailwind directives to your CSS

```javascript
@tailwind base;
@tailwind components;
@tailwind utilities;
```

## Changing package.json file's scripts

```json
{
  "name": "banking-app-with-tailwind",
  "version": "1.0.0",
  "description": "",
  "main": "index.js",
  "scripts": {
    "build": "tailwindcss -i ./input.css -o ./main/output.css",
    "watch": "tailwindcss -i ./input.css -o ./main/output.css --watch"
  },
  "keywords": [],
  "author": "Moid Alam",
  "license": "ISC",
  "devDependencies": {
    "tailwindcss": "^3.3.4"
  }
}
```

## After changing package.json file's scripts commands and running commands

```commands
npm run build
npm run watch
```
