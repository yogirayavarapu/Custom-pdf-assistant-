# Custom PDF Assistant

Custom PDF Assistant is a tool that leverages the open-source Google PaLM LLM to convert PDF content into embeddings and utilizes FAISS vector databases to efficiently retrieve answers to user queries.
## Features

- Converts PDF content into embeddings using Google PaLM LLM.
- Utilizes FAISS vector databases for efficient query retrieval.
- Easy to deploy and run locally.

## Live Demo

You can access the live demo of the application [here](https://custom-pdf-assistant.streamlit.app/).

![Custom PDF Assistant](imgs/upload.png)

## Installation

### Prerequisites

- Python 3.10
- Google PaLM API key (or OpenAI API key if preferred)

### Instructions

1. Clone the repository:
    ```sh
    git clone https://github.com/NandaKishoreYadav/Custom-PDF-Assistant.git
    ```
2. Obtain your Google PaLM API key for free from [Google AI Studio](https://aistudio.google.com/app/apikey) and paste it in the `.env` file. If you prefer to use OpenAI, obtain an API key from OpenAI and use it.

3. Open a command prompt from the project directory and create a new virtual environment:
    ```sh
    python -m venv myenv
    ```
4. Activate your environment:
    - On Windows:
        ```sh
        myenv\Scripts\activate
        ```
    - On Linux:
        ```sh
        source myenv/bin/activate
        ```
5. Install the necessary dependencies:
    ```sh
    pip install -r requirements.txt
    ```
6. Run the application:
    ```sh
    streamlit run app.py
    ```

## Usage

Once the application is running, you can upload a PDF file and start querying its content. The system will convert the PDF into embeddings and use the FAISS vector database to retrieve answers based on your queries.

### Note

Sometimes the prompts may give errors due to the use of the open-source model. If you encounter such issues, change the prompt and try again; it should work fine.


## Contact

If you have any questions or feedback, please feel free to reach out.

Thank you for using Custom PDF Assistant! 😊
