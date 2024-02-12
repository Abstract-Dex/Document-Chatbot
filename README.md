# Document-Chatbot

Small document chatbot using LlamaIndex and Llama-2

The data is taken from various wikipedia articles and then stored in text files. The chatbot uses LlamaIndex to index the text files, and store it in Chroma vector database. The Llama-2 is then used to query the database and get the relevant information. However, if the response is incomplete, then the chunk size and overlap may be varied to get the complete response.

[View notebook here](https://nbviewer.org/github/Abstract-Dex/Document-Chatbot/blob/main/main.ipynb)
