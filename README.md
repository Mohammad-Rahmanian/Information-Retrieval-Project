# Information Retrieval Project

This project aims to retrieve relevant documents from a collection of Persian news articles using boolean and ranked retrieval methods.

## Phase 1: Preprocessing and Boolean Retrieval

In this phase, we preprocess the documents by tokenizing, stemming, and removing stop words. We then create a positional index to handle phrase search. Phrases can be declared using double quotes (""). The NOT operator can be declared using an exclamation mark (!).

To retrieve documents using boolean retrieval, we use the most frequent terms and phrases in the query to find relevant documents.

## Phase 2: Ranked Retrieval

In this phase, we use the tf-idf weighting scheme and cosine similarity to rank the documents based on their relevance to the query. We also use the Jaccard similarity coefficient to compare the query with the documents.

To improve the efficiency of the ranked retrieval, we use champion lists to reduce the number of documents that need to be compared.

## Usage

To run the program, follow these steps:

1. Clone the repository
2. Install the required packages using `pip install -r requirements.txt`
3. Run the `preprocess.py` script to preprocess the documents
4. Run the `boolean_retrieval.py` script to retrieve documents using boolean retrieval
5. Run the `ranked_retrieval.py` script to retrieve documents using ranked retrieval

## Conclusion

This project demonstrates the use of boolean and ranked retrieval methods to retrieve relevant documents from a collection of Persian news articles. The preprocessing and indexing steps are crucial for efficient retrieval, and the use of champion lists can significantly improve the performance of the ranked retrieval.

