# CookEasy
# 🍽️ CookEasy – Smart Food Recommendation App

**CookEasy** is an intuitive and visually appealing web application built using **React** that helps users discover recipes based on **cuisine preferences** and **available ingredients**. The app leverages the **Spoonacular API** to fetch real-time, dynamic, and delicious recipe suggestions.

---

## 📌 Problem Statement

In today’s fast-paced world, people often find it hard to decide *what to cook* or *what to eat*. Factors like available ingredients, cuisine cravings, dietary restrictions, or even mood play a big role in food choices. Traditional recipe websites don't adapt to these needs in real-time.

---

## 💡 Our Solution

**CookEasy** solves these problems through:
- A **search bar** for entering ingredients you have
- **One-click category buttons** for popular cuisines like 🍕 Italian, 🥡 Chinese, 🍜 Ramen, and more
- Instant recipe suggestions fetched from Spoonacular API
- Responsive and elegant design with seamless navigation

---

## ✨ Key Features

| Feature | Description |
|--------|-------------|
| 🔍 **Ingredient-based Search** | Users can type ingredients (e.g., “chicken, tomato”) to get matching recipes |
| 🍽️ **Cuisine Categories** | Choose from over 20+ cuisines like Indian, Mexican, Vegan, BBQ, etc. |
| ⚡ **API Integration** | Recipes are fetched dynamically from [Spoonacular](https://spoonacular.com/food-api) using two endpoints: ingredient-based & cuisine-based |
| 📷 **Recipe Cards** | Recipes are shown with images and titles in a clean UI |
| 🔄 **Client-side Routing** | Powered by `react-router-dom` for seamless navigation |
| 🧪 **Scalable Layout** | Clean component structure with `screens/`, `components/`, and `assets/` folders |
| ❤️ **Future Scope** | Add features like Save to Favorites, filters for diet, calories, and steps view |

---

## 🔧 Technologies Used

- **React** + **Vite**
- **React Router DOM**
- **Spoonacular API**
- **HTML/CSS** (custom styling using `App.css`, `cuisine.css`)
- **JavaScript (ES6+)**

---

## 🔑 APIs Used

1. **Cuisine-based Recipes Endpoint**  
   ```
   https://api.spoonacular.com/recipes/complexSearch?cuisine=Italian&number=10&apiKey=0f4f027583d749f0b2d29c04319406aa
   ```

2. **Ingredient-based Recipes Endpoint**  
   ```
   https://api.spoonacular.com/recipes/findByIngredients?ingredients=chicken,tomato&number=10&apiKey=0f4f027583d749f0b2d29c04319406aa
   ```

---

## 📂 Folder Structure

```
src/
├── App.jsx              // Main component with homepage UI
├── main.jsx             // Entry point with router
├── components/          // Reusable UI components (e.g., Navbar)
├── screens/             // Page views like Home and Recipes
├── styles/              // CSS files (App.css, cuisine.css)
├── assets/              // Logos, food images if needed
```

---

## 🚀 Getting Started

```bash
git clone https://github.com/your-username/CookEasy.git
cd CookEasy
npm install
npm run dev
```

---

## 🧠 Authors

- **Anmol Tripathy** – `22bcsd34`
- **Parjanya Mishra** – `22bcsf91`
- **Bivash Bishmit Mohanty** – `22bcsf97`

---

## 📌 Final Note

> CookEasy is more than just a recipe site — it's a personalized, fast, and fun way to discover food that matches your cravings, mood, or kitchen inventory. 🍱🍲🌮
