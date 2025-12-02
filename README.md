# 🎯 react-rating-widget

A simple, customizable **Star Rating UI widget** built with **React + Vite**.
This project was created as a hands-on learning exercise to practice essential React concepts such as component structure, state management, event handling, conditional rendering, and reusable UI components.

<p align="center">
  <img src="./screenshot.png" alt="App Screenshot" width="500"/>
</p>

---

## 🚀 Live Demo

**GitHub Pages:** [https://ryanaxondev.github.io/react-rating-widget](https://ryanaxondev.github.io/react-rating-widget)

---

## ✨ Features

- ⭐ Interactive 5-star rating system
- 🎨 Customizable colors, headings, and feedback messages
- 🖱️ Hover effects for dynamic star highlighting
- 💬 Real-time feedback text based on selected rating
- 🪟 Modal popup confirming the submitted rating
- 🔁 Reset state after closing the modal
- 🧩 Reusable components (`Button`, `Star`, `Modal`)
- ⚡ Built with Vite for fast development and HMR
- 🔍 ESLint + Prettier configured for clean, consistent code

---

## 📚 What I Learned (Educational Section)

This project was created as my first React learning project. It helped me practice several important concepts:

### **🔹 Component-Based Architecture**

Breaking the UI into small, reusable pieces:

- `Rating` → container component (logic + state)
- `Star` → presentational component
- `Modal` → conditional UI
- `Button` → reusable UI element

### **🔹 React State Management (useState)**

Learned how to manage:

- `rating`
- `hover`
- `submitted`

And how UI reacts to state changes.

### **🔹 Event Handling**

- Click events for rating selection
- Hover events for previewing stars
- Resetting the UI on modal close

### **🔹 Props & Configurability**

The `Rating` component accepts:

- `heading`
- `color`
- `feedbackMessages`

This makes the component flexible and reusable.

### **🔹 Conditional Rendering**

Used to:

- Show feedback only after selecting a star
- Display modal only when “Submit” is clicked
- Change star color based on hover vs selected rating

### **🔹 Code Quality Tools**

Configured and used:

- **ESLint** (with react-hooks & react-refresh)
- **Prettier** (with recommended rules)
- **Vite** build system

---

## 🛠️ Technologies Used

- **React 19**
- **Vite 7**
- **JavaScript (ES6+)**
- **ESLint + Prettier**
- **CSS**

---

## 📁 Project Structure

```
react-rating-widget/
├── src/
│   ├── components/
│   │   ├── Rating.jsx
│   │   ├── Star.jsx
│   │   ├── Modal.jsx
│   │   └── Button.jsx
│   ├── assets/
│   ├── App.jsx
│   ├── main.jsx
│   └── index.css
│
├── public/
│   └── favicon.ico
│
├── eslint.config.js
├── prettier.config.js
├── vite.config.js
├── package.json
└── README.md
```

---

## 📦 Installation & Running the Project

### 1. Clone the repository

```bash
git clone https://github.com/ryanaxondev/react-rating-widget.git
cd react-rating-widget
```

### 2. Install dependencies

```bash
npm install
```

### 3. Start development server

```bash
npm run dev
```

---

## 🏗️ Build for Production

```bash
npm run build
```

---

## 🧹 Code Quality (ESLint & Prettier)

### ESLint features used:

- `@eslint/js` recommended rules
- `eslint-plugin-react-hooks`
- `eslint-plugin-react-refresh`
- `eslint-plugin-prettier`

### Prettier formatting rules:

- Semi-colons
- Single quotes
- Trailing commas
- 80-char line width
- 2-space indentation

Lint & format commands:

```bash
npm run lint
npm run format
```

---

## 🚀 Future Improvements

Some enhancements I might add later:

- Smooth animations for stars
- Dark/Light theme
- Ability to save rating to localStorage
- Using TypeScript
- More styling + transitions
- Turning it into an npm package

---

## 📄 License

This project is licensed under the **MIT License**.

---
