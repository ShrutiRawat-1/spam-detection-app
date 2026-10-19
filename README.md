# SMS Spam Classifier

Machine learning web app which classifies a text as Spam or Not Spam

**Live app:** (paste your Streamlit link here)

## Working
1. Cleans the text: lowercase, tokenize, remove stopwords, punctuation
2. Converts text to numbers with TF-IDF 
3. Predicts with a Voting Classifier 

## Files
- `spam-detection.ipynb`: data cleaning, EDA, model comparison
- `app.py`: Streamlit web app
- `model.pkl`, `vectorizer.pkl`: saved model and TF-IDF vectorizer
- `requirements.txt`: packages needed


## Tech 
Python, pandas, scikit-learn, NLTK, Streamlit