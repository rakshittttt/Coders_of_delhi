<h1 align="center">🔗 PeopleGraph: Intelligent Social Network Suggestions</h1>

<p align="center">
  <img src="https://img.shields.io/badge/solo-hackathon-blue.svg?style=for-the-badge" />
  <img src="https://img.shields.io/badge/built%20with-python-yellow?style=for-the-badge" />
  <img src="https://img.shields.io/badge/powered%20by-json%20data-green?style=for-the-badge" />
</p>

---

<div align="center">
  <img src="assets/overview.gif" width="700" alt="demo gif">
  <p><i>📊 Analyzing real-world connections like a pro.</i></p>
</div>

---

## 📌 What Is PeopleGraph?

> **PeopleGraph** is a lightweight but powerful recommendation engine that mimics social platform intelligence like Facebook's "People You May Know" and "Pages You Might Like" — all using structured `JSON` data.

Built solo for a hackathon, this project showcases:
- 🧠 Smart friend & page suggestions based on mutual connections
- 🧹 Data cleaning and validation of user/page data
- 🧪 Real-time testing with custom user IDs

---

## 🎯 Features

✅ Recommends new friends using mutual connections  
✅ Suggests relevant pages based on peer interests  
✅ Cleans duplicate and inactive users  
✅ Modular functions for easy extension  
✅ Built 100% in Python — no external frameworks needed!

---


## 🛠️ How It Works

```python
# Load Data
data = load_data("massive_data.json")

# Recommend People
people_you_may_know(user_id=1, data=data)

# Recommend Pages
pages_you_might_like(user_id=1, data=data)

