# Email Spam Detection

A machine learning application that classifies emails/SMS as spam or legitimate messages.

## Features
- Real-time spam detection through a Streamlit web interface
- Uses Naive Bayes classifier trained on SMS/email data
- Displays prediction results with clear visual indicators

## Project Files
- `Spam_detection.ipynb`: Jupyter notebook with data exploration, preprocessing, and model development
- `spam_detector.py`: Streamlit application for the user interface
- `vectorizer.pkl`: Saved TF-IDF vectorizer for text processing
- `model.pkl`: Saved Naive Bayes classification model
- `spam.txt`: Dataset containing labeled spam and ham messages

## Technology Stack
- Python
- Streamlit
- scikit-learn
- NLTK
- Pandas & NumPy

## How to Run
1. Install requirements: `pip install -r requirements.txt`
2. Run the Streamlit app: `streamlit run spam_detector.py`