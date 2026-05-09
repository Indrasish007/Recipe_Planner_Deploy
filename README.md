# 🍽️ Recipe Planner App — [Personalized Recipe Planner](https://recipeplanner-opal.vercel.app/)

# 🍽️ Recipe Planner — Your Personal Meal Planning Assistant

A modern and beautiful **React + Vite** application for discovering recipes, saving favorites, planning meals, and tracking nutrition — all powered by **Firebase** and the **Spoonacular API**.  
Designed for simplicity, speed, and a smooth user experience. 🚀

---

## ✨ Features

✔️ 🔐 **User Authentication** (Firebase)  
✔️ 🔍 **Search Recipes** using Spoonacular API  
✔️ ⭐ **Save & Manage Favorites**  
✔️ 🗓️ **Daily Meal Planner**  
✔️ 🍎 **Nutrition Tracking**  
✔️ 📄 **Export Recipes to PDF** (jsPDF)  
✔️ 📊 **Charts & Analytics** (Recharts)  
✔️ 🎨 **Modern UI** using Tailwind CSS  
✔️ 🛠️ **Admin Tools** for importing custom recipes  

---

## 🧱 Tech Stack

| Category | Tools |
|---------|-------|
| **Frontend** | React 19, Vite |
| **Styling** | Tailwind CSS |
| **Backend / Services** | Firebase Auth + Firestore |
| **API** | Spoonacular API |
| **Extras** | jsPDF, Recharts, lucide-react |
| **Linting** | ESLint |

---

## 🚀 Getting Started

### 1️⃣ Clone the project
```bash
git clone <your-repo-url>.git
cd RecipePlanner
```

### 2️⃣ Install dependencies
```bash
npm install
```

### 3️⃣ Create your `.env` file  
⚠️ **Do NOT upload real API keys to GitHub.**  
Use this template:

```
VITE_SPOONACULAR_API_KEY=your_spoonacular_api_key

VITE_FIREBASE_API_KEY=your_firebase_api_key
VITE_FIREBASE_AUTH_DOMAIN=your_project.firebaseapp.com
VITE_FIREBASE_PROJECT_ID=your_project_id
VITE_FIREBASE_STORAGE_BUCKET=your_project.appspot.com
VITE_FIREBASE_MESSAGING_SENDER_ID=your_sender_id
VITE_FIREBASE_APP_ID=your_app_id
```

### 4️⃣ Start development server
```bash
npm run dev
```
Then open 👉 **http://localhost:5173**

---

## 📁 Project Structure

```
src/
├── components/        # UI components (RecipeCard, Sidebar, Modals)
├── pages/             # Screens (Dashboard, MealPlanner, Admin, Auth)
├── utils/             # Helpers, cleaning functions
├── firebase.js        # Firebase setup
├── App.jsx            # Route entry
└── main.jsx           # App mount point
```

---

## 🔥 Firebase Setup (Quick Guide)

1. Go to **Firebase Console** → Create Project  
2. Enable **Authentication** → Email/Password  
3. Create **Firestore Database**  
4. Copy config → paste inside `.env`  
5. Done! 🚀

---

## 🧪 Available Scripts

| Command | Description |
|---------|-------------|
| `npm run dev` | Start dev server |
| `npm run build` | Build production files |
| `npm run preview` | Preview production build |
| `npm run lint` | Run ESLint |

---

## 📝 Notes

⚠️ **Never commit `.env` to GitHub**  
⚙️ Ensure Node **18+**  
📡 Spoonacular API has usage limits  
🔥 Firestore rules must match your collection names  

---

## 🤝 Contributing

Pull requests are welcome!  
1. Fork the repo  
2. Create your feature branch  
3. Commit changes  
4. Open PR 🚀  

---

## 📜 License

This project currently has **no license**.  
If you want it to be open-source, add a `LICENSE` file (MIT recommended).

---

## ❤️ Acknowledgements

- React + Vite  
- Tailwind CSS  
- Firebase  
- Spoonacular API  
- jsPDF  
- Recharts  
- lucide-react Icons  
