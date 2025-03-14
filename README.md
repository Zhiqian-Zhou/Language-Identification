# Language-Identification

## Project Overview
This project focuses on **language identification** using **character-based language models**. The dataset consists of text samples from six languages: English, Spanish, Dutch, German, Italian, and French. The model is trained on **trigram-based language modeling** with **smoothing techniques** to enhance performance.

## Features
- **Dataset**:
  - Training data: 30k sentences per language.
  - Test data: 10k sentences per language.
- **Character-level Trigrams** for language modeling.
- **Smoothing Techniques** applied to improve predictions.
- **Evaluation Metrics**: Accuracy, precision, recall.

## Installation
1. Clone the repository:
   ```sh
   git clone <repository_url>
   cd language-identification
   ```
2. Install dependencies:
   ```sh
   pip install numpy pandas nltk sklearn
   ```

## Dataset Details
- Training and test data from **Wortschatz Leipzig Corpora**.
- Files used:
  - `deu_trn.txt` (German training data)
  - `eng_trn.txt` (English training data)
  - `fra_trn.txt` (French training data)
  - `ita_trn.txt` (Italian training data)
  - `nld_trn.txt` (Dutch training data)
  - `spa_trn.txt` (Spanish training data)

## Model Development Process
1. **Data Preprocessing**:
   - Tokenization of text.
   - Generating trigrams for character-level language modeling.
2. **Model Training**:
   - Building frequency distributions for trigrams.
   - Applying smoothing techniques.
3. **Evaluation & Testing**:
   - Running the model on test data.
   - Measuring classification accuracy.

## Future Improvements
- Implement **deep learning-based approaches** (e.g., RNNs, Transformers).
- Optimize smoothing techniques for better accuracy.
- Expand to support additional languages.

## Authors
- **Zhihao Chen**
- **Zhiqian Zhou**

## References
- Wortschatz Leipzig Corpora.
- NLP research on language identification.

