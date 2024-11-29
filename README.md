## SummarEase

SummarEase is an AI-powered automatic summarization tool designed to process PDFs, PPTs, and Word documents. It leverages state-of-the-art NLP models to extract, refine, and generate high-level summaries of academic research papers, technical documentation, and general content. By enhancing BERT-based models for contextual understanding, and integrating the OpenAI API for abstractive summarization, SummarEase delivers summaries with a significant improvement in quality.

### Features

- **Multi-Document Support**: Upload PDFs, PPTX, and DOCX files for summarization.
- **Abstractive Summarization with OpenAI API:** Generates concise summaries with a human-like quality.
- **Contextual Understanding with BERT:** Uses BERT to improve understanding of academic papers and technical content.
- **State-of-the-Art Summarization:** Achieved a 22% improvement in summarization quality, particularly for research papers and technical documentation.

### Tech Stack

- **HTML & CSS:** For the frontend design and structure.
- **Bootstrap:** Frontend framework for responsive UI.
- **Python:** Backend development and summarization logic.
  
#### Libraries

- **Transformers (Hugging Face):** For utilizing BERT and other state-of-the-art NLP models.
- **OpenAI API:** For abstractive summarization of content.
- **PyPDF2:** Extract text from Word documents.
- **Werkzeug:** Secure file upload handling.

### Model Deployment

The summarization model has been enhanced and published on Hugging Face, providing easy access for users and researchers to utilize and improve upon the summarization capabilities.

### Getting Started

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/YourUsername/SummarEase.git
   ```

2. **Navigate to the Project Directory:**
   ```bash
   cd SummarEase
   ```

3. **Install Dependencies:**
   ```bash
   pip install -r requirements.txt
   ```
4. **Set Up Environment Variables:**
   Add your OpenAI API key in a .env file
   ```bash
   OPENAI_API_KEY=your_api_key
   ```
   
4. **Run the Flask Application:**
   ```bash
   python app.py
   ```
4. **Access the Application:**
   - Open your browser and go to http://localhost:5000 to start using SummarEase.

### Contributing

We welcome contributions to make DiagnosticHub even more feature-rich and accurate. Please fork the repository, make your changes, and submit a pull request.

### License

This project is licensed under the [MIT License](LICENSE).

### Acknowledgements

- Thanks to the Hugging Face community for providing the resources for model deployment.
- Special thanks to OpenAI for the GPT-3 API, which powers abstractive summarization.
Grateful for the open-source libraries that make this project possible.
