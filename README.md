# Sentimental_Analysis_Mini_project

This mini project performs sentiment analysis on user-provided text using machine learning techniques. It classifies text into **positive**, **negative**, or **neutral** sentiments and includes a user-friendly web interface for real-time predictions.

---

## 🚀 Features

- 🧹 Text preprocessing (cleaning, tokenizing, vectorizing)
- 🔍 Sentiment prediction using a trained ML model
- 🌐 Web-based UI using Flask + HTML/CSS
- 📝 Input box for users to enter custom text
- 📊 Output displays predicted sentiment label

---

## 🗂️ Project Structure

Sentimental_Analysis_Miniproject/
│
├── static/ # CSS and static assets
├── templates/ # HTML templates for the web interface
├── model/ # Trained sentiment analysis model (pickle file)
├── app.py # Flask web application
├── train_model.py # Script to train and save sentiment model
├── preprocess.py # Text preprocessing functions
└── README.md # Project overview

yaml
Copy
Edit

---

## 🧰 Requirements

- Python 3.6+
- Flask
- scikit-learn
- pandas
- nltk

Install them using:

```bash
pip install -r requirements.txt
💡 How to Use
Train the Model (if not already trained):

bash
Copy
Edit
python train_model.py
Run the Web App:

bash
Copy
Edit
python app.py
Open your browser and go to http://127.0.0.1:5000/ to enter text and get sentiment predictions.

🎯 Applications
Customer feedback analysis

Social media sentiment tracking

Review summarization

📌 Future Scope
Extend to multilingual sentiment analysis

Add emoji or sarcasm detection

Deploy on cloud (e.g., Render, Heroku)
