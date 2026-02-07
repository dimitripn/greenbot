# 🌱 Greenbot

Greenbot is a tiny GitHub Actions bot that keeps your contribution graph green by planting a random number of “seeds” (commits) every day.

Each day, it:
- Chooses a random number of commits (1–3)
- Appends lines to a `.keepalive` file
- Commits and pushes automatically
- Makes your GitHub garden grow 🌿

---

## ✨ Features
- 🌱 Random commits per day (1–3)
- ⏰ Runs automatically at 00:00 WIB (UTC+7)
- 🤖 Fully automated using GitHub Actions
- 🪴 Lightweight (only updates one file)

---

## 📂 How It Works
1. GitHub Actions runs on a daily schedule  
2. It randomly decides how many commits to make  
3. It appends lines into `.keepalive`  
4. It commits and pushes those changes  
5. GitHub updates your contribution graph  

---

## 🚀 Setup

1. Fork or clone this repository
2. Ensure GitHub Actions are enabled
3. The workflow will run automatically based on the schedule
4. You can also trigger it manually from the Actions tab

---

> This project is for learning GitHub Actions and automation. Real contributions should still come from real work.
