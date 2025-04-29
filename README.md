## Description
This repo contains a Colab-friendly multimodal RAG even though I've used 2 LLMs for it.
Usually people dissect the document in 3 parts i.e. Tables, Charts, Text. After dissecting, they create summary of all the 3 datatypes using a text and vision based LLMs. For retrevial they match the query to the summary and then try to find the relevant data.
But this approached uses what is called a Nomic Embeddings by Nomic.ai where they use the embedding model to embed the entire document instead of dissecting and then embedd. This is a SOTA embedding model. And then Ive used a vision based LLM to pass they query and the relevant doc page to answer the query.

Normal Multimodal RAG Architecture
![image](https://github.com/user-attachments/assets/b7211adb-0f5d-471d-8b92-535f96e2c2a7)

Nomic Embedded Multimodal RAG Architecture
![image](https://github.com/user-attachments/assets/e2a107aa-e1dd-4729-9d26-459825402806)
