## Prerequisites

Before you can start using the Llama2 Medical Bot, make sure you have the following prerequisites installed on your system:

- Python 3.9 or higher
- Required Python packages (you can install them using pip):

        - chainlit~=1.1.306
        - faiss_cpu
        - sentence_transformers
        - Transformers specifically CTransformers
        - bitsandbytes
        - accelerate
        - torch
        - pypdf
        - langchain~=0.2.6      

## Installation

1. Clone this repository to your local machine.

    ```bash
    git clone https://github.com/your-username/langchain-medical-bot.git
    cd langchain-medical-bot
    ```

2. Create a Python virtual environment (optional but recommended):

    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows, use: venv\Scripts\activate
    ```

3. Install the required Python packages:

    ```bash
    pip install -r requirements.txt
    ```

4. Download the required language models and data. Please refer to the Langchain documentation for specific instructions on how to download and set up the language model and vector store.
   
