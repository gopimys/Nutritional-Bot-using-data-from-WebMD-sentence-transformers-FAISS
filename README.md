# This is web applications built using Python Flask.

# Nutritional-Bot-using-data-from-WebMD-sentence-transformers-FAISS
creating a nutrition search engine powered by data from WebMD using sentence-transformers, FAISS

### Building Nutrition Chatbot using sentence-transformers , FAISS and BeautifulSoup
- **scrape the internet for content that we can use to supplement an LLM like ChatGPT's**
- **we'll gather information from [Nourish by WebMD](https://www.webmd.com/diet/default.htm) and process articles to create a databank of sources on nutrition that will be used to power a nutrition chatbot.**
-  **using sentence-transformers(multi-qa-MiniLM-L6-cos-v1 model since it is extremely fast ) and FAISS(indexing algorithms b META AI) to create a vector store index to connect the databank we created to an LLM like ChatGPT**
**- we initialize self.embeddings to a numpy array of shape (0,384)—this is because the multi-qa-MiniLM-L6-cos-v1 Sentence Transformers model provides a vector with 384 dimensions**


[Pinecone's incredible FAISS tutorial](https://www.pinecone.io/learn/series/faiss/vector-indexes)
Sentence Transformers [documentation](https://www.sbert.net/docs/pretrained_models.html)
