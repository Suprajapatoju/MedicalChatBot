"BioMistral Medical RAG Chatbot using BioMistral Open Source LLM"

This project implements a Retrieval-Augmented Generation (RAG) chatbot designed to provide accurate medical information using BioMistral-7B, an open-source large language model. The chatbot retrieves relevant information from a document titled "healthyheart.pdf" and generates coherent responses that are informed by this external knowledge source.

Key Technologies & Frameworks
LangChain: Used to integrate and orchestrate the LLM, embedding model, and vector store.

BioMistral-7B: The large language model used for generating the chatbot's responses, fine-tuned for medical information retrieval and generation tasks.

PubMedBert: A transformer-based embedding model specialized for medical and biomedical texts, used to create high-quality sentence embeddings for effective retrieval of relevant information from the document.

Chroma (Vector Store): A vector storage solution that indexes document embeddings and enables efficient retrieval during query processing.

Models Used:
LLM: BioMistral-7B, which powers the natural language generation aspect of the chatbot.

Embedding Model: PubMedBert, used to convert medical document text into vector embeddings for similarity searches.
