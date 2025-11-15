# 🥗 Eat Smart – Evolve  
AI-powered nutrition & wellness application built using React, TypeScript, Vite, Tailwind CSS, and ShadCN UI.  
Eat Smart Evolve helps users track meals, understand nutrition, get recommendations, and develop healthier eating habits.

---

## ✨ Features

### 🍽️ 1. Smart Meal Logging
- Add and manage daily food items easily
- Auto-categorization (Breakfast, Lunch, Dinner, Snacks)

### 📊 2. Nutrition Analysis Dashboard
- Macro tracking (Calories, Protein, Carbs, Fats)
- Daily & weekly charts using Recharts
- Progress insights

### 🧠 3. AI Food Analyzer (Future Integration)
- User enters any food item
- AI predicts calories & macros
- Smart health suggestions

### 🥗 4. Meal Plan Suggestions
- Recommendations based on goals:
  - Weight Loss
  - Weight Gain
  - Maintenance Diet

### 🎛️ 5. Modern UI with ShadCN Components
- Beautiful responsive design
- Cards, Inputs, Drawers, Dialogs, Charts
- Framer Motion animations

---

## 🏗️ Tech Stack

### Frontend
- React + TypeScript
- Vite
- Tailwind CSS
- ShadCN UI
- Recharts
- Framer Motion

### Tools
- ESLint + Prettier
- PostCSS
- TSConfig paths
- Vite optimized build

---

## 📂 Project Structure

eat-smart-evolve/
│── src/
│   ├── components/
│   │   ├── ui/ (ShadCN Components)
│   │   ├── charts/
│   │   ├── navbar/
│   │   ├── dashboard/
│   │   ├── diet/
│   │   └── utils/
│   ├── pages/
│   │   ├── Home.tsx
│   │   ├── Dashboard.tsx
│   │   ├── DietPlanner.tsx
│   │   └── Profile.tsx
│   ├── App.tsx
│   └── main.tsx
│
│── public/
│── package.json
│── vite.config.ts
│── tailwind.config.ts
│── tsconfig.json

---

## 🚀 How to Run the Project

### 1. Install dependencies
npm install

### 2. Start development server
npm run dev

### 3. Build the project
npm run build

### 4. Preview production build
npm run preview

---

## 🔗 Deployment (Render / Vercel / Netlify)

### Vercel
- Framework: Vite
- Build command: npm run build
- Output: dist

### Render
- Environment: Static Site
- Build command: npm install && npm run build
- Publish directory: dist

---

## 🛠️ API Integration Ready
The project is structured to support backend/AI integration easily.

Example folders for future API:
- src/api/food.ts
- src/api/user.ts
- src/api/ai.ts

---

## 🌟 Future Implementations

### 🔮 1. AI Food Recognition
Take a photo → AI identifies food → Calculates calories.

### 🤖 2. AI Nutrition Assistant Chatbot
Ask: “What should I eat for 40g protein dinner?”

### 🧮 3. Custom Diet Goal Engine
Modes:
- Keto
- Vegetarian
- High-protein
- Weight goals

### 📝 4. Cloud Sync & User Accounts
Using Firebase, Supabase, or NEON DB.

### 🫀 5. Health Tracking
- Daily steps
- Water intake reminder
- Sleep tracking
- BMI & body measurement charts

### 📈 6. Advanced Analytics Dashboard
- Weekly nutrition patterns
- Deficiency warnings
- Personalized predictions

### 🛒 7. Smart Grocery List Generator
Auto-list based on user's weekly meal plan.

---

## 🧑‍💻 Contributing
Pull requests are welcome. Follow TypeScript and project structure guidelines.

---

## 📜 License
MIT License.

