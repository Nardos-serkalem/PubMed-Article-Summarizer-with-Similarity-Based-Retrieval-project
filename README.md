# PubMed Article Summarizer

The **PubMed Article Summarizer** is a streamlined tool for finding and summarizing relevant PubMed research articles based on any user-defined search query. I implemented this tool using FAISS for efficient similarity search, enabling users to retrieve semantically similar articles in response to their query. The project features a Gradio-based user interface for easy interaction, returning concise summaries with titles, authors, links, and abstracts for each retrieved article.

## Features
- **Web Scraping with BeautifulSoup**: Retrieves real-time data from PubMed to ensure up-to-date search results.
- **FAISS Indexing for High-Speed Retrieval**: Uses FAISS (Facebook AI Similarity Search) to create a quick and efficient index of article embeddings.
- **Semantic Embeddings with SentenceTransformer**: Encodes article abstracts to improve the relevance and accuracy of retrieval results.
- **Dynamic Data Retrieval**: Uses BeautifulSoup to scrape real-time data from PubMed, ensuring up-to-date results.
- **User-Friendly Gradio Interface**: An intuitive interface for entering search topics and retrieving organized summaries without requiring technical expertise.
- **Organized Summaries**: Returns article titles, authors, abstracts, and direct links to PubMed.

