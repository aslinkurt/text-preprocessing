# text-preprocessing
This project focuses on text preprocessing and corpus analysis using a dataset of sales records. It walks through the core stages of preparing and analyzing textual data:  Building and normalizing a corpus  Tokenization, stop word removal, and lemmatization  Generating analytical visualizations and a word cloud to explore text patterns

# Text Preprocessing and Visualization

## 📄 Description

This project focuses on **text preprocessing and corpus analysis** using a dataset of sales records. It walks through the core stages of preparing and analyzing textual data:

- Building and normalizing a corpus  
- Tokenization, stop word removal, and lemmatization  
- Generating analytical visualizations and a word cloud to explore text patterns

---

## 🧪 Text Processing Overview

1. **Data Loading**  
   Used a CSV file of sales records with at least 100 entries.

2. **Corpus Creation & Normalization**  
   Combined text columns and cleaned data (lowercase, punctuation removal, whitespace stripping).

3. **Text Preprocessing**  
   - Tokenized using NLTK  
   - Removed stopwords  
   - Lemmatized using spaCy

4. **Visualizations**  
   - Bar chart of top word frequencies  
   - Boxplot of word length distribution  
   - Word cloud (supplementary)

---

## 📊 Sample Outputs

- **Bar Chart**: Most common lemmas  
- **Boxplot**: Distribution of word lengths  
- **Word Cloud**: Visual of term usage

---

## ⚙️ Dependencies

```bash
pip install pandas matplotlib nltk spacy wordcloud
python -m nltk.downloader stopwords punkt
python -m spacy download en_core_web_sm

