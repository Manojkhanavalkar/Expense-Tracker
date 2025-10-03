# Expense Tracker

**Author:** Manoj Khanavalkar  
**Built for:** Practice & learning  
**About:** A beginner-friendly web application to track expenses using vanilla JavaScript and localStorage.

---

## 🧾 Overview

This is a simple Expense Tracker application built using:

- HTML  
- CSS  
- JavaScript  

It lets you:

- Add expenses (name + amount)  
- Delete individual expenses  
- See a running total of all expenses  
- Persist your data using **localStorage** so the expenses remain even after page reload  

I built this to practice dynamic data loading, DOM manipulation, and usage of localStorage. It was fun and educational.

---

## 📁 File Structure

Expense-Tracker/

├── index.html
├── style.css
└── script.js

yaml
Copy code

- `index.html` — the app’s markup  
- `style.css` — styling (dark theme, layout, buttons)  
- `script.js` — JavaScript logic for adding, deleting, calculating total, and localStorage  

---

## 🚀 Usage / How to Run

1. Clone or download this repository.  
2. Open `index.html` in your browser (double-click or serve via a simple HTTP server).  
3. Use the form to enter an expense name and amount, then click **Add Expense**.  
4. The expense will appear in the list below and the total will update.  
5. Use the **Delete** button next to any expense to remove it.  
6. Data is stored in localStorage — refresh the page and your data remains.

---

## 🧠 Key Concepts Learned & Used

- DOM Manipulation: creating elements, appending to lists  
- Event Handling: listening for form submit, click events  
- Array Methods: `push`, `filter`, `reduce`  
- localStorage: `setItem` / `getItem` + `JSON.stringify` / `JSON.parse`  
- Conditional UI updates: show/hide sections based on state  

---

## 🔧 Possible Enhancements / Future Ideas

- Add **editing** functionality for existing expenses  
- Introduce **quantity or frequency** (weekly, monthly)  
- Add **date/time** to each expense  
- Add filtering or sorting (by date, amount)  
- Add **clear all** button  
- Improve UX, animations, responsiveness  
- Use charts or graphs to visualize expense breakdown  
- Move to a framework (React, Vue) or backend for persistence  

---

## 📌 Notes & Tips

- Make sure your browser supports localStorage (modern browsers do).  
- In dev tools → Application → Local Storage you can inspect stored data under the key `"expenses"`.  
- Use meaningful `data-` attributes (e.g. `data-id`) when rendering delete buttons to identify which expense to remove.  
- After every change (add / delete) always update both your in-memory array **and** localStorage, then re-render UI.

---

Thank you for checking out my project!  
Built with ❤️ by **Manoj Khanavalkar** — I hope you find it useful and fun to expand upon.
