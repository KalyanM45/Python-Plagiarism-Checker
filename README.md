# Plagiarism Detection Script

This Python script performs plagiarism detection on a set of text documents using the Term Frequency-Inverse Document Frequency (TF-IDF) approach. It calculates the cosine similarity between pairs of documents to identify potential cases of plagiarism.

## Usage

1. Place the text documents (`.txt` files) in the same directory as the script.
2. Run the script:

    ```bash
    python plagiarism_detection.py
    ```

3. The script will output pairs of documents along with their cosine similarity scores, indicating potential plagiarism.

## Requirements

Make sure to install the required dependencies before running the script:

```bash
pip install scikit-learn
```

## How it works

- The script reads all `.txt` files in the current directory and stores their content in a list (`student_notes`).
- It then vectorizes the text using the TF-IDF vectorizer from scikit-learn.
- Cosine similarity is calculated between each pair of documents to identify potential plagiarism.
- The script outputs pairs of documents along with their cosine similarity scores.

## Contributing

Feel free to contribute by submitting issues or pull requests. 

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgments

- The script uses scikit-learn for TF-IDF vectorization and cosine similarity calculations.
