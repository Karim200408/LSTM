# 🧠 AI Dataset Management Platform

This project is a **Streamlit-based web application** that allows users to:
- Upload CSV datasets
- Add questions and feedback related to each dataset
- Manage datasets (view, delete, track actions)
- Authenticate users (Login/Register system)
- Admin review functionality
- Track all user actions (uploads, views, deletes) in a clean `dataset_actions` table

---

## 📦 Features

- 🔐 **User Authentication**
  - Secure login and registration
  - Password hashing
  - Admin account creation
  
- 📁 **Dataset Management**
  - Upload new datasets (stored as separate SQL tables)
  - View and preview uploaded datasets
  - Delete datasets
  - Dataset names based on user input

- 🧠 **Question and Answer Management**
  - Add questions for each dataset
  - Edit or delete questions
  - Admin ratings for questions (Excellent, Good, Needs Improvement)
  
- 📊 **Action Tracking**
  - Every upload, view, delete is logged in `dataset_actions`
  - Easy to audit and analyze platform activity

- 🖼️ **Custom Logo Support**
  - Personalized AI-themed logo displayed in the UI

---

## 🚀 Tech Stack

| Technology | Purpose |
|:---|:---|
| Python 3 | Core programming language |
| Streamlit | Web UI framework |
| SQLite | Lightweight embedded database |
| Pandas | CSV file handling and data manipulation |
| Base64 | Handling images for web embedding |

---

## 🏗️ Project Structure

