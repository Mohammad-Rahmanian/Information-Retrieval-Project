
# Information Retrieval Project 🌐📖

## Introduction 📌
Welcome to the Information Retrieval Project. This robust tool is designed for the retrieval of relevant information from a comprehensive dataset of Persian news articles. Leveraging boolean and ranked retrieval methods, it's an essential resource for those working in fields like natural language processing and information retrieval.

## Features 🌟
- Positional Index Implementation
- Boolean Retrieval
- Ranked Retrieval with Cosine and Jaccard Scoring
- Champion Lists for Efficient Searching

## System Requirements 💻
- Python 3.x
- Necessary Python Libraries

## Installation 🔧
```bash
git clone [repository-url]
cd [repository-directory]
pip install -r requirements.txt
```

## Usage 📘

### 1. Positional Index Implementation
- **Load Documents**: Start by loading your dataset of Persian news articles.
- 
- **Preprocess Documents**: Tokenize, stem, and remove stopwords to prepare the dataset for indexing.
- 
- **Create Positional Index**: Construct an index to efficiently locate words in documents.

- **Answering Query & Show Result**: Perform boolean searches with phrases and NOT operators.

### 2. Ranked Retrieval
- **Cosine Score Calculation**: Rank documents based on tf-idf and cosine similarity to the query.
  
- **Jaccard Score Calculation**: Use Jaccard similarity for an alternate ranking method.
  
- **Create Champion Lists**: Build lists to optimize retrieval by focusing on top-ranked documents.

- **Show Ranked Result**: Display results in order of relevance, based on the chosen scoring method.

