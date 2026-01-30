# Agriculture ML Chatbot 🌾

This project is an ML-based chatbot that answers agriculture-related questions using a CSV dataset.

## Features
- Answers only from dataset (no external API)
- Uses Machine Learning (TF-IDF + Cosine Similarity)
- FastAPI backend
- Ready for mobile app integration

## Technologies Used
- Python
- FastAPI
- Pandas
- Scikit-learn

## How it Works
1. Questions from CSV are converted to vectors using TF-IDF
2. User question is matched using cosine similarity
3. Best matching answer is returned

## Deployment
- Backend hosted on Render
- Code hosted on GitHub

## Author
Aravind
