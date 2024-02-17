readme_content = """
# Chat with Multiple PDFs

This is a Streamlit web application that allows users to chat with a conversational AI model about the content of multiple PDF documents. The application utilizes natural language processing (NLP) techniques to extract text from PDF files, split the text into chunks, and build a conversational retrieval chain for responding to user queries.

## Features

- Upload multiple PDF documents.
- Ask questions about the content of the uploaded documents.
- Receive responses from a conversational AI model trained on the document content.

## Installation

1. Clone this repository to your local machine:

    ```bash
    git clone https://github.com/Jihen-Belhoudi/MultiPDF-Chat-App.git
    ```

2. Navigate to the project directory:

    ```bash
    cd MultiPDF-Chat-App
    ```

3. Install the required Python packages:

    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. Run the Streamlit application:

    ```bash
    streamlit run app.py
    ```

2. In the browser, upload one or more PDF documents using the file uploader.
   
3. Click the "Process" button to extract text from the uploaded documents and build the conversational model.

4. Enter questions about the content of the documents in the text input field and press Enter.

5. View the responses from the conversational AI model in the main panel.

## Contributing

Contributions are welcome! Here's how you can contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your_feature`).
3. Make your changes.
4. Commit your changes (`git commit -am 'Add some feature'`).
5. Push to the branch (`git push origin feature/your_feature`).
6. Create a new Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

This project utilizes several open-source libraries and resources:

- [Streamlit](https://streamlit.io/)
- [PyPDF2](https://pythonhosted.org/PyPDF2/)
- [langchain](https://github.com/langchain)
- [OpenAI](https://openai.com/)
- [Hugging Face](https://huggingface.co/)


"""

with open('README.md', 'w') as f:
    f.write(readme_content)
