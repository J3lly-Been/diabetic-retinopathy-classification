# Neural Network Classification for Diabetic Retinopathy

## Overview

This project aims to develop a neural network model for classifying diabetic retinopathy using a dataset from the UCI Machine Learning Repository. The project addresses class imbalance and employs advanced techniques to enhance model performance, including hyperparameter tuning and early stopping.

## Project Structure

- **Data Preparation**: Standardized and cleaned the dataset, handled class imbalance using SMOTE, and prepared data for training.
- **Neural Network Development**: Constructed and trained a neural network with early stopping to optimize performance.
- **Performance Evaluation**: Evaluated the model's accuracy and loss to ensure effectiveness.

## Dataset

The dataset is sourced from the UCI Machine Learning Repository and includes features related to diabetic retinopathy, with a target variable indicating the presence of the condition.

## Technologies Used

- **TensorFlow**: For building and training the neural network model.
- **scikit-learn**: For data preprocessing, splitting, and handling class imbalance.
- **imblearn**: For applying SMOTE to address class imbalance.
- **Matplotlib & Seaborn**: For data visualization.

## Installation

To run this project, install the required Python libraries:

```bash
pip install numpy pandas matplotlib seaborn tensorflow scikit-learn imbalanced-learn ucimlrepo
```

## Usage

1. **Clone the Repository**:

    ```bash
    git clone https://github.com/J3lly-Been/diabetic-retinopathy-classification.git
    cd diabetic-retinopathy-classification
    ```

2. **Prepare the Data and Train the Model**:

    Open the Jupyter notebook `diabetic-retinopathy-classification.ipynb` and follow the instructions within the notebook to load, clean, preprocess the dataset, build, train, and evaluate the neural network model.

## Results

- **Test Accuracy**: 78.9%
- **Test Loss**: 0.51

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

- [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/index.php)
- [TensorFlow](https://www.tensorflow.org/)
- [scikit-learn](https://scikit-learn.org/)
- [imblearn](https://imbalanced-learn.org/)
- [Matplotlib](https://matplotlib.org/)
- [Seaborn](https://seaborn.pydata.org/)
