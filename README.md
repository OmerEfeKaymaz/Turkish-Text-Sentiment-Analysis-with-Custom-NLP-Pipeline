# Turkish Text Sentiment Analysis with Custom NLP Pipeline 🇹🇷💬

This project presents a comprehensive Natural Language Processing (NLP) pipeline tailored specifically for **Turkish-language sentiment analysis**. It enables the classification of text polarity (positive, negative, neutral) and basic **topic extraction** from sources like social media posts, product reviews, and news articles.

---

## 🚀 Project Highlights

* **Language-Specific Preprocessing**: Custom tokenization, normalization, stopword removal, stemming and lemmatization optimized for Turkish.
* **Emoji & Emoticon Handling**: Converts emojis and emoticons into meaningful textual representations.
* **Text Vectorization**: Supports both `TF-IDF` and `Word2Vec` for feature extraction.
* **Model Training**: Classification using `Support Vector Machines (SVM)` and `Random Forest Classifier`.
* **Evaluation Metrics**: Accuracy, F1-score, and confusion matrices.

---

## 📁 Structure

```text
📦Turkish_Text_Sentiment_Analysis
 ┣ 📜 Turkish_Text_Sentiment_Analysis_with_Custom_NLP_Pipeline.ipynb
 ┣ 📄 README.md
```

---

## 🧠 Key Technologies

* Python 3.x
* scikit-learn
* nltk
* gensim
* matplotlib / seaborn
* pandas / NumPy

---

## ⚙️ Installation & Usage

1. Clone the repository:

```bash
git clone https://github.com/yourusername/turkish-text-sentiment-nlp.git
cd turkish-text-sentiment-nlp
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Run the notebook:

```bash
jupyter notebook Turkish_Text_Sentiment_Analysis_with_Custom_NLP_Pipeline.ipynb
```

---

## 📊 Sample Output

> Example classification results:

* "Bu ürün harika, herkese tavsiye ederim!" → **Positive**
* "Hiç memnun kalmadım, param boşa gitti." → **Negative**
* "Ürün geldi ama henüz denemedim." → **Neutral**

Confusion matrix, word clouds, and top features will be displayed inside the notebook.

---

## 📜 License

### MIT License

Copyright (c) 2024 Ömer Efe Kaymaz

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

---

## 👨‍💻 Developer

**Ömer Efe Kaymaz**
[LinkedIn](https://www.linkedin.com/in/omerefekaymaz) • [GitHub](https://github.com/OmerEfeKaymaz)
