# 🗓️ Habit Tracker App

This is a web application for tracking daily habits. It allows users to:  
✅ Add daily habits  
✅ Change the tracking date  
✅ Monitor and review their progress  

All data is stored in a MongoDB database, and the application is built with Flask.

---

## 🚀 Features

- Manage and track daily habits
- Change the tracking date
- Save and view results
- MongoDB-based data storage
- Flask backend

---

## 🛠️ Installation

Follow these steps to get started:

1. **Clone the repository:** 

  bash
  git clone https://github.com/your-username/habit-tracker-app.git
  cd habit-tracker-app

2. **Set up a vitrual enviroment and install dependencies:**

  python -m venv venv
  source venv/bin/activate     
  venv\Scripts\activate        
  pip install -r requirements.txt

3. **Create a MongoDB Atlas account**

   3.1. Get your MongoDB connection strring (it looks like:
   mongodb+srv://<user>:<password>@cluster0.mongodb.net/<dbname>?retryWrites=true&w=majority)
   3.2. Create a .env file and paste your connection string

4. **Create .flaskenv file**

  Inside: 
    FLASK_APP=app.py
    FLASK_ENV=development

5. **Run the app:**

  flask run






  

   
