# 📝 Text Tokenization in NLP  

This notebook (`text_tokenization.ipynb`) covers **different tokenization techniques** used in Natural Language Processing (NLP). Tokenization is the process of splitting text into smaller units (tokens) such as words, subwords, or characters.  

---

## 📌 Topics Covered  

1. **Word Tokenization (Whitespace / Split Method)**  
   - Splits text by spaces.  
   - Simple, but fails with punctuation.  

2. **Regex Tokenization**  
   - Uses regular expressions (`re.findall`) to extract words.  
   - More control over punctuation & patterns.  

3. **NLTK Word Tokenizer**  
   - Uses `nltk.word_tokenize` for smarter tokenization.  

4. **Sentence Tokenization**  
   - Splits text into sentences using punctuation.  

5. **SentencePiece / Subword Tokenization**  
   - Used in BERT, GPT, and modern LLMs.  
   - Breaks words into subword units.  

6. **Byte Pair Encoding (BPE)**  
   - Splits text into frequent subword units.  
   - Efficient for large vocabularies.  

7. **Character-Level Tokenization**  
   - Splits text into characters.  
   - Useful for Chinese/Japanese or typo-sensitive tasks.  

---
