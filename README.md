# 💖 Valentine Proposal Website

A cute and interactive Valentine proposal webpage built using pure HTML, CSS, and JavaScript.

This project creates a romantic experience with:
- Animated hearts
- Escaping “No” button 😝
- Confetti celebration 🎉
- Background music 🎵
- WhatsApp sharing 💬
- Mobile-friendly responsive design

---

## ✨ Features

### 💘 Interactive Proposal
- User is asked:
  > "Will you be my Valentine?"

### 😅 Escaping "No" Button
- The "No" button moves away when hovered or touched.

### 💖 Celebration Mode
When the user clicks **Yes**:
- Romantic success message appears
- Confetti animation starts
- Floating hearts animate across screen
- Music starts playing

### 💬 WhatsApp Sharing
- Allows sharing the acceptance message directly on WhatsApp.

### 📱 Responsive Design
- Works on desktop and mobile devices.

---

## 📂 Project Structure

```text
project/
│
├── index.html
└── README.md
```

---

## 🚀 How To Run

### Option 1 — Open Directly
1. Save the file as:
   ```text
   index.html
   ```

2. Double click the file  
   OR

3. Open it in any browser:
   - Chrome
   - Edge
   - Firefox
   - Safari

---

### Option 2 — Run Using VS Code Live Server

1. Install:
   - Live Server extension in VS Code

2. Right click `index.html`

3. Click:
   ```text
   Open with Live Server
   ```

---

## 🛠 Technologies Used

- HTML5
- CSS3
- Vanilla JavaScript
- Canvas API

---

## 🎵 Music Source

Background music is loaded from:
- Pixabay Audio CDN

---

## 📸 Screens Included

### Initial Screen
- Romantic proposal card
- Floating hearts
- Two buttons:
  - Yes 💕
  - No 😝

### Success Screen
- Celebration message
- Confetti animation
- Share button

---

## ⚡ Main Functionalities

### Escaping Button Logic
```javascript
function moveButton() {
    const x = Math.random() * 260 - 130;
    const y = Math.random() * 140 - 70;
    noBtn.style.transform = `translate(${x}px, ${y}px)`;
}
```

---

### WhatsApp Sharing
```javascript
function share() {
    const text = "I just said YES to Ayush 💖🥰";
    const url = `https://wa.me/?text=${encodeURIComponent(text)}`;
    window.open(url, "_blank");
}
```

---

### Confetti Animation
Implemented using:
- HTML Canvas
- requestAnimationFrame()

---

## 📱 Mobile Compatibility

Supports:
- Touch events
- Responsive sizing
- Mobile browsers

---

## 💡 Future Improvements

Possible upgrades:
- Add custom photos
- Add countdown timer
- Add personalized messages
- Add Fireworks animation
- Add custom background music upload
- Store responses in database
- Deploy online using Vercel/Netlify

---

## 🌐 Deployment Options

You can host this project for free using:

- Vercel
- Netlify
- GitHub Pages

---

## ❤️ Author

Made with love by Ayush 💖

---
