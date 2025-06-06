# Project is a user-friendly news research tool designed for effortless information retrieval. Users can input article URLs and ask questions to receive relevant insights from the stock market and financial domain.
![bot](https://github.com/user-attachments/assets/9ff6a4d8-25dc-4722-87cb-41a506bc11ff)


# Features:
Load URLs or upload text files containing URLs to fetch article content.
Process article content through LangChain's UnstructuredURL Loader
Construct an embedding vector using OpenAI's embeddings and leverage FAISS, a powerful similarity search library, to enable swift and effective retrieval of relevant information
Interact with the LLM's (Chatgpt) by inputting queries and receiving answers along with source URLs.

# Usage
The web app will open in your browser.
On the sidebar, you can input URLs directly.
Initiate the data loading and processing by clicking "Process URLs."
Observe the system as it performs text splitting, generates embedding vectors, and efficiently indexes them using FAISS.

# Requirements:
The embeddings will be stored and indexed using FAISS, enhancing retrieval speed.
The FAISS index will be saved in a local file path in pickle format for future use.
One can now ask a question and get the answer based on those news articles
main.py: The main Streamlit application script.
requirements.txt: A list of required Python packages for the project.
faiss_store_openai.pkl: A pickle file to store the FAISS index.
