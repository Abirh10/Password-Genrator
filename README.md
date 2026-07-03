# 🔐 Password Generator

A clean, responsive, and customizable password generator built with **HTML**, **CSS**, and **Vanilla JavaScript**. Generate strong passwords instantly by choosing the desired length and character types, while receiving real-time password strength feedback.

---


## ✨ Features

- 🔑 Generate secure random passwords
- 📏 Adjustable password length (6–24 characters)
- 🔠 Include uppercase letters
- 🔡 Include lowercase letters
- 🔢 Include numbers
- 🔣 Include special symbols
- 📋 One-click copy to clipboard
- ✅ Copy success confirmation icon
- 💪 Real-time password strength meter
- 📱 Fully responsive design
- 🎨 Modern gradient UI

---

## 🛠️ Built With

- HTML5
- CSS3
- JavaScript (ES6)
- Font Awesome Icons
- Google Fonts (Montserrat)

---

## 📂 Project Structure

```
Password-Generator/
│
├── index.html
├── styles.css
├── script.js
└── README.md
```

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/your-username/password-generator.git
```

### 2. Navigate to the project

```bash
cd password-generator
```

### 3. Open the project

Simply open **index.html** in your browser.

No installation or dependencies are required.

---

## ⚙️ How It Works

1. Select your desired password length.
2. Choose which character types to include:
   - Uppercase letters
   - Lowercase letters
   - Numbers
   - Symbols
3. Click **Generate Password**.
4. Copy the generated password using the copy icon.
5. View the password strength indicator.

---

## 🧠 Password Strength Calculation

The password strength meter evaluates passwords using:

- Password length
- Uppercase characters
- Lowercase characters
- Numbers
- Symbols

Strength levels:

- 🔴 Weak
- 🟡 Medium
- 🟢 Strong

---

## 📋 Copy to Clipboard

Click the copy icon to instantly copy the generated password.

After copying successfully:

- The copy icon changes into a green checkmark.
- It automatically resets after 1.5 seconds.

---

## 🎨 UI Highlights

- Modern gradient background
- Clean card layout
- Interactive buttons
- Smooth animations
- Custom checkboxes
- Dynamic strength meter
- Responsive spacing and typography

---

## 📌 Future Improvements

- Ensure at least one character from every selected category is included
- Prevent ambiguous characters (O, 0, l, I)
- Password history
- Dark/Light mode toggle
- Entropy score calculation
- Custom symbol selection
- Save user preferences
- Password expiration recommendations
- Keyboard shortcuts
- Accessibility improvements
