# 🍽️ FlavorAI – Frontend

This is the **React + Vite** frontend of the FlavorAI web app. It provides a sleek, responsive user interface to browse, create, and manage AI-powered recipes.


## 🛠 Tech Stack

- ⚛ React + TypeScript
-  Vite
-  Tailwind CSS
-  React Router
-  React Hook Form
-  Axios (with token-based interceptors)
-  Material UI
---

## Getting Started

### 1. Clone the frontend repository

```bash
git clone https://github.com/your-username/flavorai-frontend.git
cd flavorai-frontend
```
### 2. Install dependencies
```bash
npm install
```
### 3. Create environment file
```bash
cp .env.example .env
```
4. Run development server
```bash
npm run dev
```

## OPTIONAL

### Docker
If you're using Docker:
```bash
docker build -t flavorai-frontend .
docker run -p 5173:5173 flavorai-frontend
```


Key feature is Axios Interceptors which allows to get quitly Authorization JWT tokens (access+refresh).

## Known issues:
- First slow load due to bundle size. Used components of Material UI library for faster development but increased bundle size. 

## Suggestions:
-  Adding feature "Editing" of user's recipes.
-  AI integreation for creating recipes.
-  Nutrient information for recipes
-  Likes and comments for recipes. 

