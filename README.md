
**PubMed Article Summarizer**
The PubMed Article Summarizer provides an efficient way to find and summarize PubMed research articles related to any user-defined query. I implemented this tool using the FAISS library for high-speed similarity search, enabling users to retrieve articles based on their semantic relevance to the query. The system scrapes PubMed for article data, encodes abstracts with SentenceTransformer embeddings, and indexes these embeddings using FAISS for streamlined retrieval. A user-friendly Gradio interface allows users to enter their search topic, retrieve relevant articles, and view a concise summary with titles, authors, links, and abstracts.

Features
FAISS Indexing for Similarity Search: FAISS (Facebook AI Similarity Search) is used to index article embeddings, providing quick retrieval of the most relevant articles based on semantic similarity.
Sentence Transformer Embeddings: Article abstracts are encoded using SentenceTransformer embeddings to create high-dimensional representations, enhancing the relevance of retrieved articles.
Web Scraping with BeautifulSoup: Articles are dynamically scraped from PubMed using BeautifulSoup to retrieve real-time article data.
Gradio Interface: A user-friendly interface built with Gradio allows users to easily input search terms and view summarized results without needing technical expertise.
Summary Display: Provides an organized summary including title, authors, abstract, and a link to each article.
