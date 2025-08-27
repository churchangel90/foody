# 🍽️ Next.js Meal App with TheMealDB API

This is a simple Next.js application that fetches and displays a **random meal** using [TheMealDB API](https://www.themealdb.com/api.php). It shows the meal's name, image, category, area, and instructions.

---

## 📦 Tech Stack

- **Next.js** – React framework
- **React Hooks** – `useState`, `useEffect`
- **TheMealDB API** – Free public food API
- **pnpm** – Fast, disk-efficient package manager

---

## 🔍 Features

- Fetches a **random meal** on page load
- Displays:
  - Meal name
  - Meal image
  - Meal category (e.g., Beef, Seafood)
  - Meal area (e.g., Italian, Mexican)
  - Instructions for preparation
- Optional: "Load another meal" button

---

## 🧑‍💻 Getting Started (using `pnpm`)

Follow these steps to clone and run the project locally:

### 1. Clone the Repository

```bash
git clone https://github.com/churchangel90/foodfeeding.git
cd app

```

## Install Dependencies with pnpm

If you don't have pnpm installed:

```bash
    npm install -g pnpm
```

```bash
    pnpm install
```

## Run the Development Server

```bash
    pnpm dev
```


## API Used
- All data is fetched from TheMealDB
- Example Endpoint

```bash
    https://www.themealdb.com/api/json/v1/1/random.php
```