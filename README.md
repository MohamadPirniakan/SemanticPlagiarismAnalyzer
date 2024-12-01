# SemanticPlagiarismAnalyzer

## Overview
PlagiarismDetectorPro is an AI-powered tool designed to detect plagiarism by comparing the semantic similarity between text documents. It uses state-of-the-art NLP models and FAISS for fast and efficient similarity searches.

## Features
- **Text Preprocessing:** Removes punctuation, numbers, and converts text to lowercase for better accuracy.
- **Sentence Embeddings:** Generates embeddings using `sentence-transformers/all-mpnet-base-v2`.
- **Similarity Search:** Uses FAISS to perform efficient similarity search and detect plagiarism.
- **Customizable Threshold:** The similarity threshold can be adjusted to fit different use cases.

## Installation
1. Clone the repository:
   ```bash
   https://github.com/MohamadPirniakan/SemanticPlagiarismAnalyzer.git
   cd PlagiarismDetectorPro
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the tool:
   ```bash
   SemanticPlagiarismAnalyzer.ipynb
   ```

## Example
Here is an example output after running the tool:
```
Plagiarism Results:
doc1.txt and doc2.txt have a similarity score of 0.97
doc3.txt and doc4.txt have a similarity score of 0.95
```

## Requirements
- Python 3.8+
- pandas
- sentence-transformers
- faiss
- numpy

## License
This project is licensed under the MIT License. Feel free to use and modify it.
