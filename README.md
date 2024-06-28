# Naive Bayes Classification on Wine Dataset

This repository contains a project demonstrating the use of Naive Bayes classifiers on the Wine dataset. The project includes data loading, preprocessing, model training, and evaluation using both Gaussian and Multinomial Naive Bayes algorithms.

## Dataset

The Wine dataset is a classic dataset used in pattern recognition and machine learning. It contains 178 samples of wine, each with 13 features and a target variable representing the class label.

## Libraries Used

- pandas
- scikit-learn

## Project Structure

- `Naive_bayes.ipynb`: The Jupyter notebook containing the code for the project.

## Steps in the Project

1. **Importing Libraries**: Import necessary libraries including pandas and scikit-learn.
2. **Loading the Dataset**: Load the Wine dataset from scikit-learn.
3. **Data Exploration**: Explore the dataset to understand its structure and contents.
4. **Data Preprocessing**: Split the dataset into training and testing sets.
5. **Training Naive Bayes Models**:
    - Train a Gaussian Naive Bayes model.
    - Train a Multinomial Naive Bayes model.
6. **Model Evaluation**: Evaluate the models using the test set and compare their performance.

## Installation

To run the code in this repository, you need to have the following libraries installed:

```bash
pip install pandas scikit-learn
```

## Usage

To use this project, simply open the `Naive_bayes.ipynb` notebook in Jupyter and run the cells. The notebook is structured to guide you through the entire process from data loading to model evaluation.

## Results

The notebook evaluates the performance of both Gaussian and Multinomial Naive Bayes models on the Wine dataset. The evaluation metrics include accuracy scores on the test set.

## Conclusion

This project provides an overview of how to apply Naive Bayes classifiers to a classification problem using the Wine dataset. It demonstrates the steps involved in training and evaluating machine learning models using scikit-learn.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
