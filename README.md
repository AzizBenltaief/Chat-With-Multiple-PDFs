📚 Chat with Multiple PDFs — Streamlit + LangChain + FAISS

This project lets you upload multiple PDF documents and ask questions about their content using an AI chatbot powered by LangChain, FAISS, Instructor embeddings, and Hugging Face models.
It processes your PDFs, embeds them, stores them in a vector database, and answers questions using a conversational retrieval chain.


🚀 Features

📄 Upload multiple PDF documents
🔍 Automatic PDF text extraction
✂️ Text chunking for efficient embedding
🤖 Embeddings using hkunlp/instructor-xl
🧠 Vector storage using FAISS
💬 Conversational memory
🔗 HuggingFaceHub LLM (e.g., FLAN-T5, Mistral, etc.)
🌐 Streamlit user interface
🎨 Custom chat bubbles for user & bot messages


🛠️ Technologies Used

Component	Library / Model
UI	Streamlit
LLM	HuggingFaceHub (flan-t5-xxl by default)
Embeddings	HuggingFaceInstructEmbeddings (Instructor-XL)
Vector DB	FAISS
Framework	LangChain
PDF Parsing	PyPDF2
Environment	python-dotenv
