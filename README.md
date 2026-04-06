# NLP Techniques on Text Data in Python

## Aim
The aim of this experiment is to implement and understand various Natural Language Processing (NLP) techniques on text data using Python. It focuses on processing textual data to extract meaningful insights through different preprocessing and analysis methods.

---

## Theory

Natural Language Processing (NLP) is a field of artificial intelligence that enables computers to understand, interpret, and manipulate human language. In this experiment, several fundamental NLP techniques are applied to text data.

### Libraries Used
- **NLTK (Natural Language Toolkit):** A powerful Python library used for working with human language data.
- **nltk.tokenize:** Used for breaking text into words and sentences.
- **nltk.corpus:** Provides access to datasets such as stopwords.
- **nltk.stem:** Used for stemming and lemmatization.
- **nltk.probability:** Used for frequency distribution of words.

### Commands Used
- `nltk.download()` – Used to download required datasets like punkt, stopwords, and wordnet.
- `word_tokenize()` – Splits text into individual words (tokens).
- `sent_tokenize()` – Splits text into sentences.
- `stopwords.words()` – Retrieves common stopwords in a language.
- `PorterStemmer().stem()` – Reduces words to their root form.
- `WordNetLemmatizer().lemmatize()` – Converts words to their base dictionary form.
- `pos_tag()` – Assigns grammatical tags to words.
- `FreqDist()` – Calculates frequency distribution of words.

### Concepts Covered
1. **Tokenization**  
   Breaking text into smaller units such as words or sentences.

2. **Stop Word Removal**  
   Eliminating commonly used words (e.g., "is", "the", "and") that do not add significant meaning.

3. **Stemming**  
   Reducing words to their root form by removing suffixes.

4. **Lemmatization**  
   Converting words to their meaningful base form using vocabulary and morphological analysis.

5. **Part-of-Speech (POS) Tagging**  
   Identifying grammatical roles such as nouns, verbs, adjectives, etc.

6. **Word Frequency Count**  
   Counting occurrences of each word in the text to analyze importance.

---

## Conclusion
This experiment provides a practical understanding of essential NLP techniques using Python. By applying tokenization, stop word removal, stemming, lemmatization, POS tagging, and frequency analysis, we can effectively preprocess and analyze textual data. These techniques form the foundation for advanced NLP applications such as text classification, sentiment analysis, and machine learning models.
