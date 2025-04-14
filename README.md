---

# 🪟 Modal Window Project

A simple and responsive modal window implementation using HTML, CSS, and JavaScript. This project demonstrates how to open and close modal popups with smooth animations and multiple closing methods — including the **Escape (Esc) key**.

## 🧪 Live Demo

👉 [View Modal Demo](https://naqeebansari2004.github.io/Modal-Window/)

## 📸 Preview

![Screenshot (27)](https://github.com/user-attachments/assets/eb826629-edeb-4987-8d60-60bbcf9b8e17)

![Screenshot (28)](https://github.com/user-attachments/assets/5ff3ed98-f073-4f29-9cbb-70d491f429a0)


---

## ✨ Features

- ✅ Click a button to open the modal
- ❌ Close modal using:
  - The close (`×`) button inside the modal
  - Clicking outside the modal (on the overlay)
  - Pressing the **Escape (Esc)** key
- 💫 Smooth fade-in and fade-out transitions
- 🧠 Clean and readable JavaScript logic
- 📱 Fully responsive for mobile and desktop

---

## ⌨️ Keyboard Support: ESC Key Functionality

This project includes keyboard accessibility by allowing users to close the modal with the `Escape (Esc)` key:

### 🔧 How It Works:

```js
document.addEventListener('keydown', function (e) {
  if (e.key === 'Escape' && !modal.classList.contains('hidden')) {
    closeModal();
  }
});
```

- Listens for a `keydown` event on the entire document
- Checks if the pressed key is `"Escape"`
- If the modal is currently open (not hidden), it triggers the `closeModal()` function

This improves accessibility and user experience for keyboard users.

---

## 📁 Project Structure

```
Modal-Window/
├── index.html
├── style.css
└── script.js
```

---

## 🚀 Getting Started

1. Clone the repository:

```bash
git clone https://github.com/naqeebansari2004/Modal-Window.git
```

2. Open `index.html` in your browser to see the modal in action.

No build tools or setup needed — it's pure HTML/CSS/JS!

---

## 💡 Use Cases

- Login or Signup popups
- Alerts or confirmations
- Announcements and notifications

---

## 🙌 Contributing

Have ideas to improve the modal window? Feel free to fork this repo and open a pull request!

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---
