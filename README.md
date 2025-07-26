# Spam/Ham Email Classifier

## Project Overview
This project is a machine learning model that classifies emails as either "spam" or "ham" (not spam) based on their content. The model is trained using a dataset of pre-labeled emails and a Decision Tree classifier. This project serves as a practical example of a text classification task in machine learning.

## Technology Stack
* **Python:** The core programming language.
* **Pandas:** Used for data manipulation and analysis.
* **Scikit-learn:** A machine learning library for model training and evaluation.

## Getting Started

### Prerequisites
To run this project, you will need to have Python installed on your machine.

### Installation
1.  Clone this repository to your local machine.
2.  Navigate to the project directory.
3.  Install the required libraries using pip:
    ```bash
    pip install pandas scikit-learn
    ```

### File Structure
* `spam_ham_dataset.csv`: The dataset containing the emails and their labels.
* `your_script_name.py`: The Python script for training and evaluating the model.

### How to Run
1.  Make sure you have the dataset file (`spam_ham_dataset.csv`) in the same directory as your Python script.
2.  Run the Python script from your terminal:
    ```bash
    python your_script_name.py
    ```
    The script will output the accuracy of the trained model.

## Model and Results
The model used in this project is a **Decision Tree Classifier**. It is trained on 80% of the dataset and evaluated on the remaining 20%. The output of the script is the model's accuracy, which indicates how often the model correctly classifies an email.
