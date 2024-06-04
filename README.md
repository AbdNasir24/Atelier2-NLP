# Atelier2-NLP

# NLP Lab: Rule-Based Methods, Regex, and Word Embeddings

## Objective
The main objective of this lab was to gain practical experience in various NLP techniques, including rule-based methods, regular expressions, and word embeddings. Specifically, we aimed to:
1. Generate a bill from a given text using regex.
2. Apply different word embedding techniques on a provided dataset.

## Part 1: Rule-Based NLP and Regex
We implemented Python code using regular expressions to extract product information from a text and generate a bill. The code parsed the text to identify product names, quantities, and prices, and formatted them into a bill format.

## Part 2: Word Embedding Techniques
We explored and applied several word embedding techniques to convert text data into numerical vectors:

### One-Hot Encoding, Bag of Words, and TF-IDF
* **One-Hot Encoding:** Represented each word as a binary vector.
* **Bag of Words:** Counted the frequency of each word in the text.
* **TF-IDF:** Assigned importance to words based on their frequency in the corpus.

### Word2Vec (Skip-gram and CBOW)
* **Skip-gram:** Predicted context words given a target word.
* **CBOW:** Predicted the target word given context words.

### GloVe and FastText
* **GloVe (Global Vectors for Word Representation):** Generated word vectors based on co-occurrence statistics.
* **FastText:** Provided word vectors based on subword information.

## Visualization
We visualized the encoded and vectorized vectors using the t-SNE (t-Distributed Stochastic Neighbor Embedding) algorithm to observe their distribution in a lower-dimensional space. This helped us understand the relationships between words in the embedding space.

## Conclusion
Through this lab, we gained hands-on experience in NLP techniques, regex, and word embeddings. We learned how to:
* Extract meaningful information from text using rule-based methods and regex.
* Represent words numerically using various embedding techniques.
* Visualize word embeddings to gain insights into semantic relationships between words.

Overall, this lab enhanced our understanding of NLP fundamentals and their practical applications.

## Tools Used
* Google Colab
* GitLab/GitHub
* SpaCy
* NLTK
* Scikit-learn (Sklearn)

