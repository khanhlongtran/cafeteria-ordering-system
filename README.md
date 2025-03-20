# 🍽️ Cafeteria Ordering System

This repository serves as the main project that integrates three key components for a **smart cafeteria ordering system**. Each component is a separate submodule for better modularity and development efficiency.

## 📂 Project Structure

```
cafeteria-ordering-system/
│── CafeteriaOrdering/                  # Backend (API & Razor Pages)
│── CafeteriaOrderingApp/               # Mobile App (Android)
│── recommend_meals_machine_learning/   # Machine Learning for meal recommendations
│── .gitmodules                         # Submodule configurations
│── README.md                           # Project documentation
```

## 🔧 Components

### 1️⃣ Backend - Cafeteria Ordering API & Razor Pages  
📌 **Repo:** [CafeteriaOrdering](https://github.com/khanhlongtran/cafeteria-ordering-prn231)  
📌 **Tech Stack:** ASP.NET Core, Razor Pages, SQL Server  

This component handles user authentication, order management, and restaurant data via RESTful APIs.

---

### 2️⃣ Mobile App - Cafeteria Ordering App  
📌 **Repo:** [CafeteriaOrderingApp](https://github.com/khanhlongtran/CafeteriaOrderingApp)  
📌 **Tech Stack:** Java, OkHttp  

This Android app allows users to browse menus, place orders, and track their purchases seamlessly.

---

### 3️⃣ Machine Learning - Recommend Meals  
📌 **Repo:** [recommend_meals_machine_learning](https://github.com/khanhlongtran/recommend_meals_machine_learning)  
📌 **Tech Stack:** Python, Flask, TfidfVectorizer, cosine_similarity

This module provides intelligent meal recommendations based on user preferences and past order history.

---

## 🚀 Getting Started

To get started, clone the repository along with its submodules:

```sh
git clone --recurse-submodules https://github.com/khanhlongtran/cafeteria-ordering-system.git
cd cafeteria-ordering-system
```

To update all submodules to their latest versions:

```sh
git submodule update --remote --merge
```

## 📜 License
This project is licensed under the MIT License.

