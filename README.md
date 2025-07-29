# 🎲 Tenzies Game (React)

A simple and fun **Tenzies dice game** built using **React**.  
Roll the dice until all numbers match! Click a die to **hold** its value between rolls.  
When all dice are the same, **you win**, and a confetti celebration appears! 🎉

---

## 🚀 Features

- 🎲 Roll **10 dice** at once  
- 📌 Click to **hold/unhold** a die  
- 🏆 Win condition: all dice **held** & **same value**  
- 🎉 **Confetti** celebration on winning  
- 🔄 **New Game** button resets dice automatically  
- ⌨️ **Accessibility**:  
  - Auto-focuses **New Game** button when you win  
  - Screen reader friendly win message

---

## 🧠 Tech Stack

- **Frontend:** React, Vite
- **API:** OpenRouter AI API
- **Deployment:** Netlify
- **Styling:** CSS
- **Version Control:** Git + GitHub

---

## 📸 Preview
<img width="1919" height="859" alt="image" src="https://github.com/user-attachments/assets/fd60d143-f2f9-46a3-b41e-c221710130da" />

---

## 🔗 Live Demo

👉 [Check it out here](https://rolldice-tenzies.netlify.app/)

---

## 🔐 Environment Variables

This project uses environment variables to secure your API key.

### Step 1: Create `.env` file in root

```env
VITE_OPENROUTER_API_KEY=your_openrouter_api_key_here
```
1. Clone the repo

   git clone https://github.com/Souravkr01/ChefClaude.git
   cd ChefClaude


2. Install dependencies
   
   npm install

3. Setup .env
   
   VITE_OPENROUTER_API_KEY=your_openrouter_api_key_here

4. Start the dev server

   npm run dev

## 🛠️ Tech Stack

- **React** (useState, useEffect, useRef hooks)  
- **NanoID** for unique dice IDs  
- **React-Confetti** for the celebration effect  

