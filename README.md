## 📊 Comparative Analysis of Large Language Models in Retrieval-Augmented Generation (RAG) Systems

A comprehensive performance study comparing open-source LLMs for RAG applications, conducted within 15GB GPU memory constraints.

##  Technical Stack

- **LLMs**: HuggingFace Transformers
- **Vector Database**: ChromaDB
- **Embeddings**: sentence-transformers/all-MiniLM-L6-v2
- **Document Processing**: PyPDF, LangChain
- **Environment**: Kaggle (15GB GPU memory)

## Acknowledgments

- HuggingFace for providing the model implementations
- LangChain for the RAG pipeline framework
- ChromaDB for the vector database
- Kaggle for providing the computational resources

Results
Setup Performance
Model	Model Load (s)
LLaMA 2 7B	7.04,
Falcon 7B	59.48,
Mistral 7B	165.29

Answer Generation Performance
Model	Average Answer Time (s)	Quality Rating
LLaMA 2 7B	3.08	⭐⭐⭐⭐,
Falcon 7B	8.92	⭐⭐⭐⭐,
Mistral 7B	23.78	⭐⭐⭐⭐⭐


Sample Q&A Results
Model	Answer Time	Response Quality
LLaMA 2 7B	2.21s	Concise, accurate definition,
Falcon 7B	10.06s	Brief, factual response,
Mistral 7B	20.90s	Detailed, comprehensive explanation
