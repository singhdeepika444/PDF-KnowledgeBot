# PDF-KnowledgeBot


PDF KnowledgeBot is an AI-powered chatbot built using Retrieval-Augmented Generation (RAG), designed to help users interactively query and explore PDF documents.

This application leverages:

OpenAI API for language understanding and response generation.

LangChain and LangGraph for orchestrating RAG workflows.

FAISS for efficient vector-based retrieval of information from PDF files.

Users can upload PDFs and ask questions in natural language, with the bot retrieving relevant sections and providing accurate, context-aware answers. This makes it ideal for studying, research, or quickly extracting knowledge from large documents.



# Project Structure

PDF KnowledgeBot is structured around several key components that work together to enable interactive querying of PDF documents:

LangChain: Processes the information within PDF files and orchestrates the flow to the language model. User questions are enriched with relevant sections from the PDFs, improving answer accuracy.

Vectorization (FAISS): Converts PDF content into vector embeddings for fast and precise retrieval of relevant information.

OpenAI API: Generates context-aware responses to user queries using the information retrieved from the PDFs.

LangGraph: Builds a graph structure of the processing chain, enhancing question enrichment by linking related sections of the PDF for more comprehensive answers.


# Use Cases

PDF KnowledgeBot can be applied in various domains where extracting and understanding information from documents is essential:

Research: Quickly locate relevant information in research papers and articles.

Education: Answer questions from textbooks, lecture notes, and study materials.

Business: Extract insights from reports and internal documents for decision-making.

Legal: Search for specific clauses and information in contracts and legal documents.

Healthcare: Retrieve relevant data from medical journals, clinical reports, and guidelines.

Finance: Extract key figures and insights from financial statements and reports.

Customer Support: Provide accurate and timely answers from knowledge bases and manuals.

General Knowledge: Obtain information from a variety of documents for general queries.

# Installation:

Clone the repository:
git clone https://github.com/singhdeepika444/PDF-KnowledgeBot.git
cd Chat-With-Your-PDF
Install the required libraries:
 pip install -r requirements.txt
📚 Requirements:

Python 3.12+
OpenAI API Key (Get it from OpenAI)
PDF files to query
📋 Used Libraries:

faiss-cpu==1.8.0.post1
langchain==0.3.1
langchain-community==0.3.1
langchain-core==0.3.6
langchain-openai==0.2.1
langchain-text-splitters==0.3.0
langgraph==0.2.28
langgraph-checkpoint==1.0.12
pypdf==5.0.1
streamlit==1.38.0
🚀 Running the Project:

Start the Streamlit server:
streamlit run app.py
Open the browser and go to http://localhost:8501 to access the chatbot interface.
Upload the PDF file you want to query and start chatting with the chatbot.
Ask questions related to the content of the PDF file, and the chatbot will provide answers based on the information in the document.
Enjoy interacting with the RAG PDF Chatbot!
📝 Note: The chatbot is still in development, and improvements are being made to enhance its performance and capabilities. If you encounter any issues or have suggestions for improvement, please feel free to open an issue submit a pull request, or contact me on LinkedIn.


