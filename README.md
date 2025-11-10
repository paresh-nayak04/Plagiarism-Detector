# 🧠 AI-Based Plagiarism Detector

An **AI-powered plagiarism detection web app** built using **Python** and **Streamlit**, designed to identify text similarity between documents.  
The app uses **Natural Language Processing (NLP)** techniques to compare user input with stored text data and determine whether plagiarism exists.

---

## 🚀 Features

- 📄 Upload or paste any text to check for plagiarism  
- 🔍 Detects **text similarity** between two or more documents  
- 🧩 Uses **TF-IDF Vectorization** and **Cosine Similarity** for accurate comparison  
- ⚡ Real-time results through a **Streamlit web interface**  
- 🧠 NLP-based preprocessing (tokenization, stopword removal, stemming)  
- 📊 Displays similarity percentage between documents  

---

## 🧰 Tech Stack & Libraries Used

**Languages:**  
- Python 3.x  

**Libraries:**  
- `streamlit` – for building the web interface  
- `scikit-learn` – for TF-IDF vectorization and cosine similarity  
- `nltk` – for text preprocessing  
- `numpy` & `pandas` – for data handling  
- `re` – for text cleaning  

---

## 🧮 Algorithms Used

- **TF-IDF (Term Frequency–Inverse Document Frequency):**  
  Converts text data into numerical form, giving importance to rare but meaningful words.

- **Cosine Similarity:**  
  Measures how similar two documents are based on their vector representation.

---

## 🧑‍💻 How It Works

1. Enter or upload text files in the Streamlit interface.  
2. The app cleans and preprocesses the text using NLP methods.  
3. It converts the text into TF-IDF vectors.  
4. Cosine similarity is computed between the input and existing text(s).  
5. The app displays the **plagiarism percentage** and highlights if a direct match exists.  

---

## 🧠 Future Improvements

- Integration with external sources (Wikipedia, academic papers, web scraping)  
- Highlighting plagiarized sections within the text  
- Database support for storing past checks  
