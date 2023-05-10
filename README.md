# VectorFinder

Semantic Search Engine

![Capture](https://res.cloudinary.com/divr26z8e/image/upload/v1683719363/Screenshot_2023-05-10_at_5.18.11_PM_kkf5yl.png)

Discover the power of semantic search with 'VectorFinder' - a search engine that uses artificial intelligence to provide accurate and relevant search results. 

Contents
========

 * [Requirements](#requirements)
 * [Installation](#installation)
 * [Usage](#usage)
 * [Acknowledgements](#acknowledgements)
 * [Demo Link](#demo-link)
 
### Requirements
---
To run this project, you will need the following components:
  1. Pinecone as your vector database
  2. Multi-qa-MiniLM-L6-cos-v1 multimodel retriever
  3. "deepset/electra-base-squad2" model
  4. Streamlit for building the user interface
  5. Ngrok for exposing your local server to the internet

### Installation
---
To install and run this project, follow these steps:
  1. Clone this repository to your local machine.
  2. Install any dependencies required by the project.
  3. Set up your Pinecone vector database by following the instructions provided by Pinecone.
  4. Use multi-qa-MiniLM-L6-cos-v1 multimodel retriever to generate context embeddings optimized for cosine similarity.
  5. Use "deepset/electra-base-squad2" model to find similar answers based on generated context embeddings.
  6. Develop a user interface using Streamlit that allows users to enter their queries and view the search results.
  7. Expose your local server to the internet using ngrok.


### Usage
---
To use SemantiFinder, follow these steps:
  1. Enter your query in the user interface.
  2. The query will be encoded into a vector representation using multi-qa-MiniLM-L6-cos-v1 multimodel retriever optimized for cosine similarity.
  3. The search engine will find the most similar documents to your query based on their cosine similarity with the query.
  4. The "deepset/electra-base-squad2" model will find similar answers based on generated context embeddings.
  5. The top-k most relevant answers will be displayed in the user interface.

### Acknowledgements
---
I would like to thank Pinecone, Hugging Face and Streamlit for providing their tools and resources that were instrumental in building this project.

### Demo Link

https://c156-34-168-9-45.ngrok-free.app/


