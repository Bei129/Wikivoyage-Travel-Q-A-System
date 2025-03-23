# Wikivoyage-Travel-Q-A-System

_Fei Teng (ft28), Lingyi Xu (lx28)_

This is a Retrieval-Augmented Generation (RAG) travel Q&amp;A system based on Wikivoyage.

## Task 2: Retriever

The Task 2 of the RAG project focuses on building and searching a precomputed vector index for a Wikivoyage-based travel corpus. The goal is to encode the corpus documents into embeddings, save them as an index, and then quickly retrieve the most relevant documents for any given query.

**Notes:**
- `corpus_dict.json`: A 2.3GB raw Wikivoyage corpus file containing document data (title, text, etc.); not included in the repository due to its large size.
- `ids_titles_sentences.csv`: A CSV file with document preview information used to display document titles and a brief excerpt for search results.
- `precomputed_index.pt`: A precomputed index file with document IDs and embeddings for fast retrieval.
- `ft28_lx28_task2_record.mov`: This video demo shows an interactive search session where entering a series of travel-related queries into the system. For each query, the system quickly returns the top‑k results with document IDs, titles, and preview excerpts from the Wikivoyage corpus. 