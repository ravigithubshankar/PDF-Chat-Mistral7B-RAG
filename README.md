# PDF-Chat-Mistral7B-RAG
Document pdf based Question-Answering With RAG+Mistral

This system integrates the Retrieval-Augmented Generation (RAG) framework with the Mistral model to deliver advanced document question-answering capabilities. RAG combines the strengths of information retrieval and generative modeling, allowing it to fetch relevant context from PDF documents and generate precise answers. Mistral, a state-of-the-art language model, powers the generative component, ensuring high-quality responses. The system is designed for scenarios where users need fast, accurate answers from extensive documents, making it ideal for research, legal, or educational purposes.

## Instructions to Run Document PDF-Based Question-Answering with RAG + Mistral:
### 1. Prerequisites:

    Python (>=3.8)
    GPU (optional but recommended for faster inference)
    Libraries: PyTorch, Hugging Face Transformers, FAISS, PyMuPDF (for PDF processing)
### 2. Setup Environment:

    Install required dependencies:
    pip install torch transformers faiss-cpu pymupdf sentence-transformers

### 3.If using a GPU, install GPU-specific PyTorch:
    pip install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu118

### 4. Clone the Repository:

    Clone or download the project files:
    git clone https://github.com/ravigithubshankar/PDF-Chat-Mistral7B-RAG.git
    cd PDF-Chat-Mistral7B-RAG


### 5. Start the RAG + Mistral question-answering system::
      python3 app.py

### 6.Output:

    The system will retrieve relevant document excerpts, generate a contextually appropriate answer, and display it in the console or API response.
