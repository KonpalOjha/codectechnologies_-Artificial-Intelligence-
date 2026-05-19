# codectechnologies_-Artificial-Intelligence-

# Stock Price Predictor

A machine learning project that predicts stock prices using Linear Regression.

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- yfinance

## Features
- Fetches real-time historical stock data
- Predicts next-day stock prices
- Visualizes actual vs predicted prices

## How to Run

1. Install libraries:
   pip install -r requirements.txt

2. Run Jupyter Notebook:
   jupyter notebook

3. Open:
   stock_price_prediction.ipynb

## Future Improvements
- LSTM Deep Learning Model
- Multi-stock prediction
- Live dashboard


Sentiment Analysis on Twitter Data

A simple Machine Learning project that classifies tweets into Positive, Negative, or Neutral sentiments using Natural Language Processing (NLP) techniques and the Naive Bayes Algorithm.

📌 Project Overview

This project performs sentiment analysis on Twitter-like text data.
It preprocesses tweets, converts text into numerical features using TF-IDF Vectorization, and trains a Multinomial Naive Bayes classifier to predict sentiment.

🚀 Features
Tweet text preprocessing
Stopword removal using NLTK
Stemming using Porter Stemmer
TF-IDF feature extraction
Naive Bayes classification
Confusion Matrix visualization
Predict sentiment for custom tweets
🛠️ Technologies Used
Python
Jupyter Notebook
Pandas
NumPy
NLTK
Scikit-learn
Matplotlib
Seaborn
📂 Project Structure
Sentiment-Analysis-Twitter/
│
├── sentiment_analysis.ipynb
├── README.md
└── requirements.txt
📥 Installation
1 Clone the Repository
git clone https://github.com/your-username/Sentiment-Analysis-Twitter.git
2 Navigate to Project Folder
cd Sentiment-Analysis-Twitter
3 Install Required Libraries
pip install -r requirements.txt
▶️ Run the Project

Open Jupyter Notebook and run:

jupyter notebook

Then open:

sentiment_analysis.ipynb
📊 Machine Learning Workflow
Data Collection
Text Cleaning
Stopword Removal
Stemming
TF-IDF Vectorization
Train-Test Split
Model Training
Prediction & Evaluation
🧠 Algorithm Used
Multinomial Naive Bayes

Naive Bayes is a popular algorithm for text classification problems like:

Spam Detection
Sentiment Analysis
News Classification
📈 Example Predictions
Tweet	Predicted Sentiment
I love this phone!	Positive
Worst experience ever	Negative
The movie was okay	Neutral
📷 Output

The project displays:

Accuracy Score
Classification Report
Confusion Matrix
📌 Future Improvements
Use real Twitter API data
Add Deep Learning models (LSTM/BERT)
Create Web App using Flask or Streamlit
Improve dataset size and accuracy
🤝 Contributing

Contributions are welcome.
Feel free to fork this repository and submit pull requests.

📄 License

This project is licensed under the MIT License.
