🧮 CASIO-Style Calculator (React)

A feature-rich calculator built with React, inspired by the classic CASIO desktop calculators.
This project focuses on realistic UI design, keyboard interaction, and clean component-based architecture.

✨ Features

🎨 CASIO-Inspired Interface

Boxed calculator body with borders

Solar panel design

LCD-style display

Physical, pressable buttons

⌨️ Full Keyboard Support

Numbers 0–9

Operators + − × ÷

Enter → Calculate

Backspace → Delete last digit

Esc → Clear display

💾 Memory Functions

MC – Memory Clear

MR – Memory Recall

M+ – Add to Memory

M− – Subtract from Memory

🧩 Reusable Components

Button component

Display component

⚛️ React Hooks

useState for state management

useEffect for keyboard event handling

🚀 Built using Create React App

🛠️ Tech Stack

React (Functional Components)

JavaScript (ES6+)

CSS3 (Custom styling, no UI libraries)

Create React App

📂 Project Structure
src/
 ├── components/
 │   ├── Button.jsx
 │   └── Display.jsx
 ├── App.js
 ├── App.css
 └── index.js

🚀 Getting Started
1️⃣ Clone the repository
git clone https://github.com/your-username/calculator-react.git

2️⃣ Navigate into the project
cd calculator-react

3️⃣ Install dependencies
npm install

4️⃣ Run the app
npm start


Open 👉 http://localhost:3000
 in your browser.

🎮 Keyboard Controls
Key	Action
0–9	Enter numbers
+ - * /	Operators
.	Decimal
Enter	Calculate
Backspace	Delete last input
Esc	Clear display
📸 UI Preview

CASIO-style calculator with:

Left-aligned brand label

Centered solar panel

LCD display

Physical button depth

(Add screenshots here if desired)

⚠️ Note on eval()

This project uses eval() only for learning and demonstration purposes.
For production-level applications, a custom expression parser should be used to ensure safety.

🌱 Future Enhancements

❌ Replace eval() with safe expression parsing

🔢 Add 00 key

🔊 Button click sound

🎨 Theme switch (light / dark)

📱 Mobile-first responsiveness

🧠 Advanced memory features
