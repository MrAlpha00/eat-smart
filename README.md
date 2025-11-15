🥗 Eat Smart – Evolve

Your personal AI-powered nutrition guide that helps you make healthier food choices, track meals, analyze nutritional values, and build better eating habits.

Eat Smart Evolve is built with React + TypeScript + Vite, styled using Tailwind CSS + ShadCN UI, and structured with modular, clean components.

✨ Features
🍽️ 1. Smart Meal Logging

Add foods instantly

Auto-categorization (Breakfast, Lunch, Dinner, Snacks)

Saves logs locally / API-ready

📊 2. Nutrition Analysis Dashboard

View calories, proteins, fats, carbs

Daily & weekly progress charts

Macro distribution insights

🧠 3. AI Food Analyzer (Future Integration)

Input any food item

AI predicts calories & macros

Generates health tips

🥗 4. Meal Plan Suggestions

Auto-generated meal recommendations

Based on goals (Weight loss / Gain / Normal diet)

🎛️ 5. Modern UI with ShadCN Components

Cards, Inputs, Charts, Dialogs, Drawers, Carousels

Smooth animations

Fully responsive

🏗️ Tech Stack
Frontend
Tech	Purpose
React + TS	Main framework
Vite	Faster builds & dev server
Tailwind CSS	Styling
ShadCN UI	Beautiful pre-built components
Recharts	Graphs & analytics
Framer Motion	Smooth animations
Tools & Config

ESLint + Prettier

PostCSS + Tailwind

TSConfig path aliasing

Vite optimized bundling

📂 Project Structure
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

🚀 How to Run the Project
1. Install dependencies
npm install

2. Start development server
npm run dev

3. Build
npm run build

4. Preview build
npm run preview

🔗 Deployment (Render / Vercel / Netlify)
For Vercel

Create project

Framework = Vite

Build command:

npm run build


Output folder:

dist

For Render

Environment: Static Site

Build command:

npm install && npm run build


Publish directory:

dist

🛠️ API Integration Ready

Your project already supports easy implementation of APIs:

Example folder locations:

/src/api/food.ts

/src/api/user.ts

/src/api/ai.ts

Just plug in your backend or 3rd-party API.

🌟 Future Implementations (Add these to your README)
🔮 1. AI Food Recognition (Image Input)

Upload food photo → AI identifies dish + calories.

🤖 2. Chatbot Nutrition Coach

Ask questions:

“What should I eat for dinner with 40g protein?”

🧮 3. Custom Diet Goal Engine

Weight gain / loss

Keto, Vegetarian, High-protein modes

Auto meal plans

📝 4. Cloud Sync & User Accounts

Use Firebase / Supabase / NEON DB.

🫀 5. Health Tracking

Steps

Sleep

Water reminder

Body measurements graph

📈 6. Advanced Analytics Dashboard

Weekly nutrition trends

Deficiency detection

Personalized recommendations

🛒 7. Smart Grocery List

Generate items based on meal plan.

🧑‍💻 Contributing

Pull requests are welcome!
Follow TypeScript lint rules and component structure.

📜 License

This project is open-source under the MIT License.
