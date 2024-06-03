
RAG-GPT is a versatile chatbot utilizing the OpenAI GPT Model, Langchain, ChromaDB, and Gradio to enhance document interaction. It supports functionalities for both pre-processed documents and real-time uploads, allowing users to integrate, process, and summarize PDFs or Docs seamlessly during chat sessions. The interface, built with Gradio, is designed for ease of use, and the model’s memory feature maintains a record of user interactions for personalized responses. Users can adjust settings like the GPT model's temperature to optimize performance and can view retrieved content or associated PDFs directly in the chat interface.

Running Project:

pip install gradio==4.13.0 langchain==0.0.354 openai==0.28.0 chromadb==0.4.22 pypdf==3.17.4 pandas==2.1.4


cd RAG_GPT

python3 -m venv projectenv/python3.11 -m venv projectenv

.\projectenv\Scripts\activate


terminal 1:

python src\serve.py

terminal 2:

python src\raggpt_app.py


