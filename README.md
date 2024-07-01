# MUSE: Multi-PDF Information Retrieval Chat App 🚀

MUSE (Multi-PDF Information Retrieval Chat App) is an advanced application designed to efficiently extract and retrieve information from multiple PDF documents through an intuitive chat interface.

## Key Features

- **Multi-PDF Support**: Seamlessly process and analyze multiple PDF documents simultaneously.
- **Chat Interface**: User-friendly conversational interface for querying document content.
- **Advanced NLP Techniques**: Leveraging cutting-edge Natural Language Processing for enhanced information retrieval.

## Technologies Used

- **Named Entity Recognition (NER)**: Identifies and extracts key entities such as people, locations, and organizations from the text.
- **OLLAMA**: Employed for targeted information retrieval, focusing on the most relevant passages within the PDFs.
- **LLAMA3**: Utilizes advanced language understanding for accurate question answering.

## Performance

- Achieved an 8% accuracy improvement through the integration of Named Entity Recognition.

## Potential Applications

- Beyond simple question answering, MUSE allows users to target specific entities within PDFs, opening up a wide range of potential use cases in research, academia, and business intelligence.

## Future Development

We're constantly working to improve MUSE and expand its capabilities. Future updates may include:

- Support for additional file formats
- Enhanced entity relationship mapping
- Integration with external knowledge bases

## Getting Started

Follow these steps to set up and run the MUSE app:

1. **Create a virtual environment:**
    ```sh
    conda create -p venv python==3.10
    ```

2. **Activate the virtual environment:**
    ```sh
    conda activate venv/
    ```

3. **Install the required libraries:**
    ```sh
    pip install -r requirements.txt
    ```

4. **Run the model:**
    ```sh
    ollama pull nomic-embed-text
    ```

5. **Start the application:**
    ```sh
    chainlit run app.py
    ```

**Note:** Make sure you have Ollama installed. Enter your GROQ API Key in .env file.

## Contributing

Welcome contributions to the MUSE project. 

