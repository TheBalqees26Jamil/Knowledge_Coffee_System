# ☕ Coffee Recommendation System (GUI)

## 📌 Overview

This project is a **GUI-based Coffee Recommendation System** built باستخدام PyQt6.

The application asks users about their coffee preferences (strength, milk, sweetness, flavors, iced) and provides a personalized coffee recommendation.

---

## 🎯 Objective

The goal of this project is to create an interactive system that simulates a simple **recommendation engine** using user preferences.

---

## 🛠️ Technologies Used

* Python
* PyQt6

---

## 🚀 Features

* Clean and modern GUI design
* Welcome screen with navigation
* Multiple user preference inputs:

  * Coffee strength
  * Milk level
  * Sweetness
  * Flavor preference
  * Iced or hot
* Instant recommendation based on choices
* Styled UI with colors and fonts

---

## 🧠 How It Works

1. User starts from the welcome screen
2. Answers a set of preference questions
3. The system matches answers with predefined combinations
4. Displays a recommended coffee type

---

## ☕ Recommendation Logic

The system uses a dictionary-based mapping:

* Each combination of answers → specific coffee
* If no exact match → default recommendation (Americano)


---

## 📁 Project Structure

```
Knowledge_Coffee_System/
│
├── main.py      # GUI + recommendation logic
└── README.md    # Documentation
```

---

## 💡 Example

User selects:

* Strength → A lot
* Milk → Somewhat
* Sweet → Somewhat
* Flavor → Not at all
* Iced → Not at all

### Output:

```
☕ Recommended: Mocha - Espresso with milk and chocolate.
```

---

## ⭐ Notes

* This is a rule-based recommendation system
* Can be improved using:

  * Machine Learning models
  * More coffee options
  * Better UI animations
  * User history tracking
