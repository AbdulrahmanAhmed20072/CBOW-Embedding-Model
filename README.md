# CBOW Model for Word Embeddings

This repository contains an implementation of the Continuous Bag of Words (CBOW) model to generate word embeddings using neural networks. The project demonstrates the process of embedding generation and visualization using text data.

## Features

- **Text Preprocessing**: Tokenizes text, cleans data, and builds a vocabulary.
- **Context Windows**: Generates context windows around target words.
- **One-Hot Encoding**: Encodes words into one-hot vectors for training.
- **Neural Network Training**: Implements the CBOW model to generate embeddings.
- **PCA Visualization**: Uses PCA to reduce dimensions for visualization of embeddings.

## Files

1. **`CBOW_WordEmbeddings.ipynb`**: Python script implementing the CBOW model.
2. **Dataset**: `shakespeare.txt` (example text data used for training).

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/AbdulrahmanAhmed20072/CBOW-Embedding-Model.git
   ```
2. Install the required Python packages:
   ```bash
   pip install numpy nltk matplotlib emoji
   ```

## Usage

1. Preprocess text data to tokenize and clean the input.
2. Create context windows for target words.
3. Train the CBOW model to learn word embeddings.
4. Use PCA for dimensionality reduction and visualization of embeddings.

Run the script:
```bash
python CBOW_WordEmbeddings.ipynb
```

## Outputs

- Word embeddings stored as numpy arrays.
- PCA visualizations of embeddings in 2D.

## Example

Input Sentence:
```
I am happy because I am learning.
```

Target Word: `happy`
Context Words: `['I', 'am', 'because', 'I']`
