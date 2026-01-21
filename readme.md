# Simple Banking UI

This project is a basic banking interface created using **HTML**, **CSS**, and **JavaScript**.  
It allows a user to **deposit and withdraw money**, while storing the account balance using the browser’s **localStorage**.

---

## Files Included

### 1. `index.html`
- Defines the structure of the banking interface
- Contains:
  - Balance display
  - Input field for amount
  - Deposit and Withdraw buttons
  - Error message section
- Links the external CSS and JavaScript files

---

### 2. `styles.css`
- Handles the visual styling of the application
- Includes:
  - Layout and alignment using Flexbox and Grid
  - Button styles for deposit and withdrawal actions
  - Input validation styles (valid/invalid borders)
  - Error message styling
  - Responsive design for smaller screens

---

### 3. `script.js`
- Implements the core banking logic
- Features:
  - Loads balance from `localStorage` (default: 1000)
  - Updates and displays balance dynamically
  - Validates input amount
  - Handles deposit and withdrawal actions
  - Prevents overdraft
  - Displays error messages for invalid input
  - Saves updated balance back to `localStorage`

---

## Functionality

- Deposit increases the balance
- Withdrawal decreases the balance if sufficient funds exist
- Invalid or negative input is rejected
- Balance remains saved even after page refresh

---

## Technologies Used

- HTML5
- CSS3
- JavaScript (Vanilla)
- Browser LocalStorage API

---

## How to Run the Project

1. Place all files in the same folder:
   - `index.html`
   - `styles.css`
   - `script.js`
2. Open `index.html` in a web browser
3. Enter an amount and use the Deposit or Withdraw buttons

---

## Notes

- This is a client-side application only
- No backend or database is used
- Balance is stored locally in the browser

---