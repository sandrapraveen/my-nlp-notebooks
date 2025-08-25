# 📌 Stemming in NLP

This folder contains my learnings and code implementations of **Stemming**, a text preprocessing technique in Natural Language Processing (NLP).

---

## 🔹 What is Stemming?

Stemming is the process of reducing words to their root/base form by chopping off prefixes or suffixes. The resulting stem word may not always be a valid dictionary word, but it helps standardize text for NLP tasks.

**Example:**

```
Playing → Play
Studies → Studi
```

✅ Pros: Simple and fast
❌ Cons: Sometimes produces non-meaningful stems (over-stemming or under-stemming)

---

## 🔹 Types of Stemming Used in Code

### 1. **Porter Stemmer**

* One of the most widely used stemmers.
* Applies a series of rules to strip suffixes.

### 2. **Snowball Stemmer** (Improved Porter)

* Also known as Porter2 stemmer.
* Slightly more aggressive than Porter.

### 3. **Lancaster Stemmer**

* Very aggressive stemmer.
* Sometimes over-stems words.
 
---


