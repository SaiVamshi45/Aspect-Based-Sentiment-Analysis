
# 🎬 Aspect-Based Sentiment Analysis

This project performs **Aspect-Based Sentiment Analysis (ABSA)** on Hindi movie reviews, combining traditional NLP techniques with modern transformer-based models. ABSA focuses on identifying sentiments tied to specific aspects such as **acting**, **direction**, **music**, etc.

---

## 📚 Table of Contents

- [Project Overview](#project-overview)
- [Data Preprocessing](#data-preprocessing)
- [POS Tagging](#pos-tagging)
- [Named Entity Recognition (NER)](#named-entity-recognition-ner)
- [Models Used](#models-used)
- [Acknowledgments](#acknowledgments)

---

## 📝 Project Overview

The goal of this project is to:

- Extract important aspects (e.g., *acting*, *direction*, *music*) from Hindi movie reviews.
- Analyze the sentiment (positive, negative, or neutral) related to each aspect.

We apply multiple NLP techniques and cutting-edge transformer models to improve sentiment classification accuracy and insight.

---

## 🧹 Data Preprocessing

The dataset consists of user-written **Hindi movie reviews**, which undergo the following steps:

- **Tokenization**: Breaking down sentences into individual words.
- **Stopword Removal**: Eliminating common Hindi words like `है`, `और`, `था`, etc.
- **Stemming & Lemmatization**: Reducing words to their root form to enhance feature consistency.

---

## 🧠 POS Tagging

Part-of-Speech tagging is applied to understand the grammatical structure and enhance aspect extraction.

### Techniques Used:

1. **Conditional Random Fields (CRF)**  
   - Probabilistic model for sequence labeling based on context.

2. **HMM + Viterbi Algorithm**  
   - Hidden Markov Model paired with the Viterbi decoding algorithm for optimal tag sequence prediction.

These approaches allow for more accurate syntactic analysis and improve the performance of the sentiment classification models.

---

## 🏷 Named Entity Recognition (NER)

To extract entities like **actor names**, **movie titles**, and **director names**, we used:

- **Polyglot**: A multilingual NLP library capable of handling Hindi text effectively.

NER enables a deeper understanding of review context and aspect targeting.

---

## 🤖 Models Used

We employed a mix of traditional and transformer-based models to capture sentiment at the aspect level:

1. ### 💬 Large Language Models (LLMs)
   - Help capture deep contextual cues within the reviews.

2. ### 🧠 BERT (Bidirectional Encoder Representations from Transformers)
   - Fine-tuned for **Hindi** using Hugging Face's transformers.
   - Captures bidirectional dependencies and subtle nuances in sentiment.

3. ### ⚡ DistilBERT
   - A distilled version of BERT offering faster inference with nearly the same performance.

4. ### 🚀 RoBERTa
   - A more robust and optimized version of BERT using dynamic masking and larger data sets.

---

## 🙏 Acknowledgments

This project reflects my interest in **Natural Language Processing (NLP)**, particularly for **Indian language texts**.

### Tools and Libraries Used:

- [spaCy](https://spacy.io/) – POS tagging & text preprocessing  
- [Polyglot](https://polyglot.readthedocs.io/) – Named Entity Recognition (NER)  
- [Hugging Face Transformers](https://huggingface.co/transformers/) – Pre-trained LLMs like BERT, DistilBERT, and RoBERTa  

---

## 📫 Contact

**Yasaswini Dharmavarapu**  
📧 [yasaswani.dharmavarapu@gmail.com](mailto:yasaswani.dharmavarapu@gmail.com)  
🌐 [GitHub Profile](https://github.com/Yassu-24)

---

## 📜 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

