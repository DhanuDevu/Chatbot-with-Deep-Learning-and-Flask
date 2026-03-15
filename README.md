# 🧠 AI Chatbot Using Deep Learning & Flask

This project is a machine-learning based chatbot that uses Natural Language Processing (NLP) and Neural Networks to understand user queries and respond with the correct intent. A Flask backend serves the trained TensorFlow model and renders a simple web UI for chatting.  

## 🚀 Features      
   
✔️ Deep learning model trained using TensorFlow/Keras  
       
✔️ Intent-based responses using Intents.json  
  
✔️ NLP preprocessing (tokenizing, stemming, bag-of-words)

✔️ SQLite database (database.db) for storing chat logs 

✔️ Flask API to handle predictions

✔️ Simple and clean HTML UI

✔️ Fully customizable intents and training dataset

## 📂 Project Structure
chatbot/
│── app.py                 # Flask application
│── chatbot_train.py       # Model training script
│── chatbot_model.h5       # Trained ML model
│── Intents.json           # Intent dataset
│── words.pkl              # Preprocessed vocabulary
│── labels.pkl             # Encoded label classes
│── database.db            # Local SQLite DB
│── templates/
│      └── index.html      # Chat UI

## 🛠️ Tech Stack
Component	Technology
Backend	Python, Flask
ML Model	TensorFlow / Keras
NLP	NLTK / Tokenization / BoW
Database	SQLite
Frontend	HTML, CSS, JavaScript

## 🧩 How It Works

User enters a message in the UI.

Flask sends the text to the ML model.

NLP pipeline converts the text to Bag-of-Words.

Model predicts the intent label.

Chatbot returns the mapped response from Intents.json.

## 🔧 Installation & Setup
1️⃣ Clone the Repository
git clone git@github.com:DhanuDevu/Chatbot-with-Deep-Learning-and-Flask.git
cd YourRepoName/chatbot

2️⃣ Install Dependencies
pip install -r requirements.txt   


(If requirements file not present, I can generate one.)

3️⃣ Train the Model (Optional)
python chatbot_train.py

4️⃣ Run the Application
python app.py

### Author Dhanush H N
