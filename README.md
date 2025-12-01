📘Stemming and Lemmatization in NLP

This repository contains a Jupyter Notebook demonstrating Stemming and Lemmatization, two essential text normalization techniques used in Natural Language Processing (NLP). These preprocessing steps help reduce words to their root form, enabling better performance in tasks like text classification, clustering, sentiment analysis, and information retrieval.

🚀 Features

The notebook covers:

🔹 1. Stemming

Introduction to stemming

Using Porter Stemmer, Snowball Stemmer, and Lancaster Stemmer

Comparison of outputs

Advantages & drawbacks

🔹 2. Lemmatization

Introduction to lemmatization

Using WordNet Lemmatizer

Lemmatizing nouns, verbs, adjectives, adverbs

Why lemmatization gives more meaningful results

🔹 3. Stemming vs. Lemmatization

Side-by-side comparison

When to use which

Efficiency vs. correctness

🔹 4. Practical Examples

Tokenization

Applying stem/lemma on sample text

Understanding output differences

📂 Repository Structure
├── Stemming_and_Lemmmetization.ipynb   # Jupyter Notebook  
├── README.md                            # Project documentation  
└── requirements.txt (optional)          # Libraries used  

🛠️ Requirements

Install required libraries before running the notebook:

pip install nltk


Also download NLTK resources:

import nltk
nltk.download('punkt')
nltk.download('wordnet')
nltk.download('omw-1.4')

📊 Technologies Used

Python 3

NLTK (Natural Language Toolkit)

Jupyter Notebook

📖 What You Will Learn

How text normalization improves NLP models

Difference between stems and lemmas

Practical usage of NLTK preprocessing tools

How to clean and prepare text for ML models

📝 Example Output
| Word    | Stem (Porter) | Lemma |
| ------- | ------------- | ----- |
| studies | studi         | study |
| better  | better        | good  |
| running | run           | run   |
| caring  | care          | care  |

