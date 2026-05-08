# 🍳 AroMate Server

AroMate Server is the backend API for the AroMate recipe application.

It provides recipe data storage and REST API endpoints for creating, reading, updating, and deleting recipes using a simple JSON database.

Designed for fast development and easy integration with the AroMate frontend application.

---

# ✨ Features

## 📖 Recipe API

Provides full recipe data including:

- Title
- Description
- Image URL
- Ingredients
- Cooking steps
- Difficulty
- Cooking time
- Tags
- Servings

---

## ➕ Add Recipes

Create and store new recipes dynamically through API requests.

---

## ✏️ Update Recipes

Edit existing recipe information using API endpoints.

---

## 🗑️ Delete Recipes

Remove recipes from the database easily.

---

# 📂 Project Structure

```bash
JSON-SERVER/
│
├── node_modules/
├── .gitignore
├── db.json
├── package.json
├── package-lock.json
├── README.md
└── server.js
```

# Local Development

```bash
http://localhost:5008
```

## Production

Server Link:

https://aromate-recipe-app-server.onrender.com

---

# 📌 API Endpoints

| Method | Endpoint       | Description       |
| ------ | -------------- | ----------------- |
| GET    | `/recipes`     | Get all recipes   |
| GET    | `/recipes/:id` | Get recipe by ID  |
| POST   | `/recipes`     | Create new recipe |
| PUT    | `/recipes/:id` | Update recipe     |
| DELETE | `/recipes/:id` | Delete recipe     |

---

# 📦 Example Recipe Object

```json
{
  "id": "1",
  "title": "Zucchini Noodles with Pesto",
  "description": "Low-carb alternative to pasta.",
  "image": "https://images.unsplash.com/photo-1551183053-bf91a1d81141",
  "ingredients": ["• 2 Zucchini", "• 3 tbsp Pesto"],
  "steps": ["• Spiralize zucchini", "• Mix with pesto"],
  "cookingTime": "15",
  "difficulty": "easy",
  "tags": ["low-carb", "keto"],
  "servings": "2"
}
```

# 📊 Current Database

The database currently contains:

| Category           | Count |
| ------------------ | ----- |
| Total Recipes      | 9     |
| Breakfast Recipes  | 4     |
| Healthy Recipes    | 5     |
| Quick Meals        | 3     |
| Vegetarian Recipes | 1     |
| Seafood Recipes    | 1     |

---

# 🔗 Links

## 🌐 Live Server

https://aromate-recipe-app-server.onrender.com

## 💻 Client Repository

(https://github.com/dantebesong321-code/AroMate-recipe-app.git)
