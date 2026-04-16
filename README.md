#  Fake News Detection System

This project uses Machine Learning and Natural Language Processing (NLP) to classify news articles as **Fake** or **Real**.

---

##  Features
- Text preprocessing and cleaning
- TF-IDF feature extraction
- Machine Learning classification (Logistic Regression)
- Real-time prediction system

---

##  Tech Stack
- Python
- Pandas, NumPy
- Scikit-learn
- NLTK

---

## Dataset

Due to file size limits, the dataset is not included in this repository.

Download dataset from here:  
https://www.kaggle.com/datasets/clmentbisaillon/fake-and-real-news-dataset

After downloading:
1. Extract the files
2. Place `Fake.csv` and `True.csv` inside the `data/` folder

---

## Project Structure

fake-news-detection/
│── data/
│   ├── Fake.csv
│   ├── True.csv
│
│── notebook/
│   └── fake_news.ipynb
│
│── src/
│   ├── preprocess.py
│   ├── model.py
│
│── app.py
│── requirements.txt
│── README.md
