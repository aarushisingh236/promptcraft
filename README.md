# PromptCraft – AI Prompt Playground 🧠✨

PromptCraft is a frontend React application that simulates how AI responses change based on different prompt parameters such as **temperature, creativity, role, and formality**.  
It allows users to experiment with prompts, generate mock AI responses, and save prompt history for reuse.

---

## 🚀 Features

- 📝 Enter custom prompts
- 🎛 Adjust response parameters:
  - Temperature
  - Creativity
  - Formality (Casual / Neutral / Formal)
  - Role (Teacher / Developer / Poet / Friend)
- 🤖 Generates simulated AI responses (mock logic)
- 💾 Save favorite prompts
- 🕒 View prompt history (last 10 prompts)
- 📋 Copy generated responses to clipboard
- 🎨 Clean and modern UI using Tailwind CSS

---

## 🛠 Tech Stack

- React (Vite)
- Tailwind CSS
- JavaScript
- LocalStorage (for persistence)

---

## 🧠 How It Works

The application uses a mock response generator function that dynamically builds AI-like responses based on user-selected parameters:

- **Role** determines tone (Teacher, Poet, Developer, Friend)
- **Formality** controls language style
- **Temperature & Creativity** influence randomness and expression

This allows users to understand how different prompt settings affect AI responses.

---

## 📦 Installation & Run Locally

```bash
git clone https://github.com/aarushisingh236/promptcraft.git
cd promptcraft
npm install
npm run dev
```

---

## 🌱 Future Improvements

- Compare two prompts side-by-side
- Animations using Framer Motion
- Real AI API integration
- Theme customization
- Export responses
