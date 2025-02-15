# Harry-Potter-Q-A-Chatbot-Using-RAG-LangChain-LLMs

# Overview

- Use [Langchain](https://python.langchain.com/en/latest/index.html) to **<font color='orange'>build a chatbot that can answer questions about</font>** [Harry Potter books](https://www.kaggle.com/datasets/hinepo/harry-potter-books-in-pdf-1-7)
- **<font color='orange'>Flexible and customizable RAG pipeline (Retrieval Augmented Generation)</font>**
- Experiment with various LLMs (Large Language Models)
- Use [FAISS vector store](https://python.langchain.com/docs/integrations/vectorstores/faiss) to store text embeddings created with [Sentence Transformers](https://huggingface.co/sentence-transformers/all-MiniLM-L6-v2) from 🤗. FAISS runs on GPU and it is much faster than Chroma
- Use [Retrieval chain](https://python.langchain.com/docs/modules/data_connection/retrievers/) to retrieve relevant passages from embedded text
- Summarize retrieved passages
- Leverage Kaggle dual GPU (2 * T4) with [Hugging Face Accelerate](https://huggingface.co/docs/accelerate/index)
- Chat UI with [Gradio](https://www.gradio.app/guides/quickstart)

### Models

- [TheBloke/wizardLM-7B-HF](https://huggingface.co/TheBloke/wizardLM-7B-HF)
- [daryl149/llama-2-7b-chat-hf](https://huggingface.co/daryl149/llama-2-7b-chat-hf)
- [daryl149/llama-2-13b-chat-hf](https://huggingface.co/daryl149/llama-2-13b-chat-hf)
- [mistralai/Mistral-7B-Instruct-v0.2](https://huggingface.co/mistralai/Mistral-7B-Instruct-v0.2)
