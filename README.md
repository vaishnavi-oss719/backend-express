🍲 Recipe API
A simple REST API built using Node.js, Express, MongoDB, and Mongoose to manage recipes.

🚀 Features
Create Recipe
Get All Recipes
Get Recipe By ID
Update Recipe By ID
Delete Recipe By ID
🛠️ Tech Stack
Node.js
Express.js
MongoDB Atlas
Mongoose
dotenv
Nodemon
📂 Project Structure
mongose/ │── Controllers/ │ └── recipe.controller.js │ │── Database/ │ └── config.js │ │── Models/ │ └── recipe.model.js │ │── Routes/ │ └── recipe.routes.js │ │── .env │── index.js │── package.json

http://localhost:4000

📌 API Endpoints
🔹 Create Recipe
POST /recipes

🔹 Get All Recipes
GET /recipes

🔹 Get Recipe By ID
GET /recipes/:id

🔹 Update Recipe
PUT /recipes/:id

🔹 Delete Recipe
DELETE /recipes/:id

🧾 Sample JSON
{
  "title": "Chicken Biryani",
  "ingredient": "Chicken, Rice, Onion, Tomato, Spices",
  "instructions": "Cook chicken. Add rice. Mix spices. Cook well.",
  "cookingTime": "45 minutes"
}
