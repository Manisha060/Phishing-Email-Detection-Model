🔐 Phishing Email Detection Model
📌 Project Overview
This project is a Machine Learning-based Phishing Email Detection System developed using Python and Scikit-Learn. The model analyzes email content and classifies emails as either Phishing or Safe (Legitimate) based on textual features extracted from email messages.
The primary objective of this project is to improve email security by identifying potentially malicious phishing emails and reducing the risk of cyber attacks.
🚀 Features
Email text preprocessing and analysis
Feature extraction using TF-IDF Vectorization
Machine Learning classification using Multinomial Naive Bayes
Phishing and Legitimate email detection
Model performance evaluation
Accuracy calculation and Confusion Matrix generation
🛠️ Technologies Used
Python
Pandas
Scikit-Learn
TF-IDF Vectorizer
Multinomial Naive Bayes
Machine Learning
📂 Project Structure
Plain text
Phishing-Email-Detection-Model
│
├── phishing_detector.py
├── README.md
└── requirements.txt
📊 Model Performance
Accuracy Achieved: 97.82%
Confusion Matrix:
Plain text
[[7853   82]
 [ 277 8286]]
The model successfully classifies phishing and legitimate emails with high accuracy.
▶️ How to Run
Clone the repository
Bash
git clone https://github.com/Manisha060/Phishing-Email-Detection-Model.git
Install dependencies
Bash
pip install pandas scikit-learn
Run the project
Bash
python phishing_detector.py
📈 Expected Output
Plain text
Accuracy: 0.9782

Confusion Matrix:
[[7853   82]
 [ 277 8286]]
