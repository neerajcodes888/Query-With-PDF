# Query With PDFs

## Table of Contents
- [Description](#description)
- [Features](#features)
- [Technology Stack](#technology-stack)
- [Installation](#installation)
- [Usage](#usage)
- [Demo](#demo)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgements](#acknowledgements)
- [Contact](#contact)

## Description
Query With PDFs is a Python-based web application that enables users to upload PDF files, ask questions related to the content of the PDFs, and obtain answers along with key points extracted from the documents. The application leverages state-of-the-art language understanding models to process user queries and extract meaningful information from the uploaded PDF files.

## Features
- **PDF Upload:** Users can easily upload PDF files through the user-friendly interface.
- **Question Asking:** Users can ask questions in natural language about the content of the uploaded PDFs.
- **Key Points Extraction:** The application automatically extracts key points and relevant information from the PDFs to provide concise summaries.
- **Answer Generation:** Using advanced language understanding models, the application generates accurate answers to user questions based on the content of the uploaded PDFs.

## Technology Stack
- **Python 3.8:** The primary programming language used for development.
- **Streamlit 1.0:** Streamlit is utilized as the web application framework to create interactive and responsive user interfaces.
- **Langchain Google GenAI:** Langchain Google GenAI is a cutting-edge language understanding model developed by Langchain in collaboration with Google. It is specifically tailored for extracting key points and generating answers from textual data such as PDF documents.
- **LLM (Language Learning Model):** LLM is a sophisticated language understanding model designed to process natural language queries with high accuracy and efficiency.

## Installation
1. Clone the repository to your local machine:

```bash
git clone Query-With-PDF
cd Query-With-PDFs
```
1. **Install the required dependencies:**

```bash
streamlit
google-generativeai
python-dotenv
langchain
PyPDF2
chromadb
faiss-cpu
langchain_google_genai
```
## Usage
1. **Run the application:**

```bash
streamlit run app.py
```
1. Access the application through a web browser at http://localhost:8501.
2. Upload a PDF file using the provided interface.
3. Ask questions related to the content of the uploaded PDF.
4. Receive detailed answers and key points extracted from the PDF.

## Demo
For a live demonstration, you can visit our demo website.

### Ask Questions to Your PDF
In this video, you can see how users can ask questions related to the content of their uploaded PDF files. The application provides a user-friendly interface for entering natural language queries. The advanced language understanding models process these queries to generate accurate answers based on the content of the PDF.

![Ask Question](ask_question_demo.gif)

### Get Key Points of Your PDF




In this video, users can observe how the application automatically extracts key points and relevant information from the uploaded PDFs. These key points provide concise summaries of the document's content, enabling users to quickly grasp the essential information contained within the PDF.

![Get Key Points](get_keypoints_demo.gif)

 
## Contributing
Contributions are welcome! If you have any suggestions, enhancements, or bug fixes, please feel free to submit a pull request.

## License
This project is licensed under the MIT License. See the [LICENSE](https://github.com/neerajcodes888/Query-With-PDF/blob/main/LICENSE) file for details.

## Acknowledgements
- Langchain Google GenAI for providing state-of-the-art language understanding capabilities.
- LLM for its advanced natural language processing functionalities.
- Special thanks to the contributors and developers who have contributed to this project.

## Contact

For any inquiries or support, please contact
