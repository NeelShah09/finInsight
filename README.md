# FinInsight: AI-Powered Financial Analysis Platform


[![Python](https://img.shields.io/badge/Python-3.8%2B-blue)](https://www.python.org/)
[![Gradio](https://img.shields.io/badge/UI-Gradio-FF6B6B)](https://www.gradio.app/)

FinInsight is an AI-driven platform designed to democratize financial education by providing clear, contextual explanations of financial terms and concepts using advanced NLP techniques. Built with a Retrieval-Augmented Generation (RAG) pipeline and the Llama2-7b-chat-hf model, it empowers users to navigate complex financial landscapes with confidence.

## Features

- **Comprehensive Explanations**: Definitions, significance, usage, and implications of financial terms.
- **Domain-Specific Focus**: Strictly answers finance-related queries, avoiding off-topic responses.
- **RAG Pipeline**: Combines vector database retrieval with LLM generation for accuracy.
- **User-Friendly Interface**: Gradio-based UI for seamless interaction.

## Architecture

FinInsight uses a  **Retrieval-Augmented Generation (RAG)**  pipeline:

1.  **Query Processing**: Tokenizes and encodes user input into vectors.
2.  **Information Retrieval**: Searches a vector database for relevant financial data.
3.  **Context Enhancement**: Combines query, retrieved data, and system prompts.
4.  **Response Generation**: Synthesizes answers using Llama2-7b-chat-hf.
5.  **Output Delivery**: Presents results via Gradio UI.

![RAG Pipeline](https://d2908q01vomqb2.cloudfront.net/f1f836cb4ea6efb2a0b1b99f41ad8b103eff4b59/2024/09/09/ML15773-01_rag_arch-1.png)
	 
## User Interface

![User-Interface](https://github.com/NeelShah09/finInsight/blob/main/user_interface.png)

## Contributors
- Neel Sachin Shah
- Abishek Manoj Sutaria
- Aaryan Manish Purohit
