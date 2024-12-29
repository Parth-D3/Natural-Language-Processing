# RAG: Document-Based Chatbot 
This repository contains files for a document based chatbot utilizing RAG principles. The data folder contains text files for 86 different sports and there information scrapped from wikipedia. The text files are later converted into chunks and these chunks are vectorised using OpenAIEmbeddings. 

### Query_data.py
Contains logic for querying the RAG application using a simple prompt template and cosine similarity for similarity calculation.

### Create_database.py
Contains logic for creating vector database using Chroma DB, OpenAIEmbeddings, and DirectoryLoader from Langchain.
