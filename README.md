# Support-Vector-Machines-for-Spam-Detection
This repository contains a Jupyter Notebook that demonstrates the implementation of Support Vector Machines (SVM) for spam detection. The notebook includes data preprocessing, feature extraction, training the SVM model, and evaluating its performance.

## Files
- `Support Vector Machines.ipynb`: The Jupyter Notebook containing the implementation of SVM for spam detection.

## Requirements
- Python 3.x
- Jupyter Notebook
- NumPy
- Matplotlib
- SciPy
- scikit-learn
- NLTK
- stemming

## Usage
1. Clone the repository:
    ```bash
    git clone https://github.com/cizodevahm/Support-Vector-Machines-for-Spam-Detection
    ```
2. Navigate to the repository directory:
    ```bash
    cd Support-Vector-Machines-for-Spam-Detection
    ```
3. Open the Jupyter Notebook:
    ```bash
    jupyter notebook Support Vector Machines.ipynb
    ```

## Implementation Details
- **Data Preprocessing**: The notebook includes functions to preprocess emails by converting them to lowercase, removing HTML tags, replacing numbers, URLs, email addresses, and dollar signs with placeholders.
- **Feature Extraction**: The notebook extracts features from emails by tokenizing, stemming, and mapping words to a vocabulary list.
- **Training the SVM Model**: The SVM model is trained using a linear kernel on a dataset of spam and non-spam emails.
- **Evaluating Performance**: The notebook evaluates the model's performance by calculating training and test set accuracy and identifying the top predictors for spam.

## License
This project is licensed under the MIT License.
