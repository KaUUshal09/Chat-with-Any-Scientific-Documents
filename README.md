# Chat with Any Scientific Documents

## Introduction

Interact seamlessly with various document formats using 'Chat with Any Scientific Documents.' Upload PDFs, DOCX, LaTeX, HTML, and image files, click 'stream,' and engage effortlessly in a conversational interface. Ask questions about your documents and receive instant, contextually relevant answers, optimizing your workflow for efficient information extraction.

## Workflow

1. **Document Loading:** Upload multiple document types, such as PDFs, DOCX, LaTeX, HTML, and images into the application. Extract the text content from the uploaded documents.

2. **Text Chunking:** Break down the extracted text into smaller, manageable chunks for better processing.

3. **Language Model:** Use a language model to generate vector representations (embeddings) for each text chunk.

4. **Similarity Matching:** When a user asks a question, compare it with the vectorized text chunks to find the most semantically similar ones.

5. **Response Generation:** Feed the selected text chunks to the language model to generate a response based on the relevant content extracted from the documents.

6. **User Interaction:** Engage in a conversational interface, posing natural language questions related to the uploaded documents.

7. **Receive Responses:** Get responses generated by the system, offering contextually relevant information from the processed documents.


## Dependencies and Installation

Install the required dependencies by running:

```bash
pip install -r requirements.txt
```


## Usage

To use the Chat with Scientific Document App, follow these steps:

1. Ensure that you have installed the required dependencies and added the OpenAI API key to the `.env` file.

2. Run the `main.py` file using the Streamlit CLI. Execute the following command:

    ```bash
    streamlit run main.py
    ```
    
The application will open in your default web browser, displaying the user interface. Follow the provided instructions to upload multiple documents (PDFs, DOCX, HTML files, LaTeX files, etc.). Use the chat interface to ask natural language questions about the uploaded documents.
