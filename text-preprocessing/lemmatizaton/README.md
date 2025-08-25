# 📝 Lemmatization

This notebook demonstrates **Lemmatization**, an important text preprocessing technique in NLP.

Lemmatization reduces words to their **base/dictionary form (lemma)** using vocabulary and grammar rules. Unlike stemming, it always produces valid words.

---

## 🔎 What is Lemmatization?

* **Stemming:** Cuts off word endings, may produce non-words.

  * Example: `running → runn`
* **Lemmatization:** Uses linguistic knowledge to return proper base forms.

  * Example: `running → run`

✅ More accurate than stemming, but slightly slower.

---

## 📘 Techniques Used in this Notebook

### 1. **WordNet Lemmatizer (NLTK)**

* Uses WordNet database.

### 2. **WordNet Lemmatizer with POS Tagging**

* Improves accuracy by considering **part-of-speech tags** (noun, verb, adjective, adverb).

### 3. **spaCy Lemmatizer**

* Uses spaCy's built-in linguistic model.
* Handles context effectively.
---

## ⚖️ Comparison with Stemming

| Feature      | Stemming          | Lemmatization        |
| ------------ | ----------------- | -------------------- |
| Speed        | Fast              | Slower               |
| Linguistic   | Rule-based only   | Vocabulary + grammar |
| Output Words | May not be real   | Always valid words   |
| Example      | `studies → studi` | `studies → study`    |

---
