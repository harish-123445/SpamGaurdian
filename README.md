# Spam Detection with Machine Learning

This project focuses on spam detection within textual data using several machine learning algorithms trained on the Spam Dataset. Various classification models such as KNN, SVM, Logistic Regression (with TF-IDF and Bag-of-Words approaches), and Multinomial Naive Bayes are employed to identify spam messages.

## Dataset and Preprocessing

The Spam Dataset is utilized for training and testing the models. The NLTK library is used for text preprocessing, which involves tasks like tokenization, removing stopwords, and stemming or lemmatization to enhance model performance.

## Algorithms and Techniques Used

The project employs the following algorithms and techniques:

- **K-Nearest Neighbors (KNN)**
- **Support Vector Machine (SVM)**
- **Logistic Regression**:
  - With both TF-IDF and Bag-of-Words approaches
- **Multinomial Naive Bayes**

Each algorithm is implemented with its specific approach to text representation and classification to compare their effectiveness in spam detection.

## Flask Application

A Flask web application is developed to provide a user-friendly interface for spam detection. Users can input text messages, and the application predicts whether the input message is spam or not based on the trained models.

## File Structure

The project files are structured as follows:

- `dataset/`: Directory containing the Spam Dataset and processed data.
- `models/`: Folder housing trained models for each algorithm.
- `main.py`: Flask application file for the web interface.
- `ML_LAB_TEST_SPAM_DETECTION.ipynb`: jupyter script for training the model

## Getting Started

To run the Flask application and perform spam detection:

1. Clone the repository:

    ```bash
    [git clone https://github.com/your-username/spam-detection.git](https://github.com/harish-123445/SpamGaurdian.git)
    ```
2. Start the Flask application:

    ```bash
    python main.py
    ```

4. Open your browser and visit `http://localhost:5000` to access the spam detection interface.


I hereby attach the output files

## Acknowledgments

- The project utilizes NLTK for text preprocessing, enhancing the models' ability to detect spam messages effectively.

Feel free to explore the project, contribute, or utilize the models for your spam detection tasks!
