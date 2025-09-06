# 🌀 QR-Code Generator

A simple web-based **QR Code Generator** built with HTML, CSS, and JavaScript.  
Users can enter any text or URL, and the app will generate a QR code dynamically using an external API.

---

## 📋 Table of Contents

- [How it works](#HowItWorks)  
- [Features](#features)  
- [Example](#example)  

---

## :notebook: How It Works

The user enters text or a URL in the input field.

When clicking Generate QR-Code, the app checks:

- ✅ If input is not empty, it calls the QR API and displays the QR code.

- ❌ If input is empty, it highlights the input and label in red for 1 second.

The QR code is displayed below the input field.

---

## 🚀 Features
- Input field with placeholder (non-selectable guide text).
- Label linked to the input for accessibility.
- Error handling when input is empty.
- Auto-generation of QR codes via the [GoQR API](https://goqr.me/api/).
- Responsive and minimal design.

---

  ## 👻 Example 
    Welcome to the Password Generator tool!
    Options:
    1. Check Current Password Strength.
    2. Generate a Unique Strong Password.
    Choose 1 or 2: 2
    Enter desired password length (minimum 8): 16
    Insert hyphens every 4 chars for readability? (Y/N): Y
  
    Generated password:
    Ab3$-kLm9-#Xy2-T0p
    
    Copy to clipboard? (Y/N): Y
    ✅ Password copied to clipboard!
  




