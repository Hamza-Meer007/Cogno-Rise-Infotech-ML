<h1>Spam Email Classification Model using Naive Bayes</h1>

<h2>Overview</h2>

This Jupyter Notebook (`main.ipynb`) uses Naive Bayes algorithm to classify emails as spam or non-spam. It trains and tests the model on a dataset of labeled emails, achieving a test accuracy of 98%.

<h2>Requirements</h2>

- Python 3.10
- Jupyter Notebook (installed via pip: `pip install notebook`)
- Scikit-learn library (installed via pip: `pip install scikit-learn`)
- NumPy library (installed via pip: `pip install numpy`)
- Pandas library (installed via pip:`pip install pandas`)

<h2>Usage</h2>

1. _Running the Notebook_

    - Open `main.ipynb` in Jupyter Notebook.
    - Run all cells to train and test the model.
2. _Understanding the Model_

    - The notebook contains code for data preprocessing, model training, and testing.
    - The model uses Naive Bayes algorithm to classify emails as spam or non-spam.
3. _Test Score_

    - The model achieves a test accuracy of 98%.

<h2>Data</h2>

- The dataset used is stored in `spam.csv`.
- Each row in the dataset represents an email, with the following columns:
    - `text`: the email text
    - `label`: the label (0 for non-spam, 1 for spam)

<h2>License</h2>

This project is licensed under the MIT License.

