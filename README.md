# IPL-Winning-Predication
IPL Winning Prediction

A Machine Learning project that predicts the probability of a team winning an IPL match based on match conditions like teams, score, overs, wickets, and target.

🚀 Project Overview

This project uses historical IPL match data to build a predictive model that estimates the winning probability of a team during a live match scenario.

It helps answer:

Who is likely to win?
How match conditions affect outcomes
Real-time win probability updates
📊 Features
Predicts win probability for both teams
Takes real-time match inputs:
Batting team
Bowling team
City
Target score
Current score
Overs completed
Wickets fallen
Interactive UI (if using Streamlit)
Trained ML model with decent accuracy
🧠 Machine Learning Approach
1. Data Preprocessing
Cleaned IPL dataset
Removed irrelevant columns
Handled missing values
Converted categorical data using encoding
2. Feature Engineering
Runs left
Balls left
Wickets remaining
Current run rate (CRR)
Required run rate (RRR)
3. Model Used
Logistic Regression / Random Forest (mention yours)
Trained on historical IPL matches
📁 Project Structure
IPL-Winning-Prediction/
│
├── data/
│   ├── matches.csv
│   ├── deliveries.csv
│
├── model/
│   ├── model.pkl
│   ├── pipeline.pkl
│
├── app.py              # Streamlit app
├── model.py            # Training script
├── requirements.txt
└── README.md
⚙️ Installation

Clone the repository:

git clone https://github.com/nitikasingh12/IPL-Winning-Predication-prediction.git
cd ipl-winning-prediction

Install dependencies:

pip install -r requirements.txt
▶️ Usage
Run the app:
streamlit run app.py

Then open in browser:

http://localhost:8501
📈 Example Input
Feature	Value
Batting Team	Mumbai Indians
Bowling Team	CSK
Target	180
Score	120
Overs	15.0
Wickets	3
📊 Output
Mumbai Indians Win Probability: 65%
CSK Win Probability: 35%
🛠️ Tech Stack
Python 🐍
Pandas & NumPy
Scikit-learn
Streamlit
Matplotlib / Seaborn (optional)
📉 Model Performance
Accuracy: ~70–80% (depends on your model)
Evaluated using:
Train/Test split
Cross-validation
⚠️ Limitations
Does not consider player-specific performance
Assumes historical patterns repeat
No real-time player stats integration
🔮 Future Improvements
Add player-level data
Use Deep Learning (LSTM)
Real-time API integration
Improve accuracy with more features
🤝 Contributing

Feel free to fork this repo and improve it!
