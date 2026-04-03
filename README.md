# Youtube_chatboat
RAG pipeline using LangChain and Groq API


A Retrieval-Augmented Generation (RAG) pipeline that answers questions about any YouTube video.

## 🛠️ Tech Stack
- **LLM:** Groq (llama-3.3-70b)
- **Embeddings:** HuggingFace (all-MiniLM-L6-v2)
- **Vector Store:** FAISS
- **Framework:** LangChain

## 🚀 How to Run
1. Open the notebook in Google Colab
2. Add your Groq API key in Colab Secrets as `GROQ_API_KEY`
3. Run all cells

## 📦 Libraries Used
- `langchain`, `langchain-groq`, `langchain-huggingface`
- `faiss-cpu`, `sentence-transformers`
- `youtube-transcript-api`
