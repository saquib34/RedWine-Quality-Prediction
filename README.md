# Red Wine Quality Prediction

## Table of Contents

- [Overview](#overview)
- [Dataset](#dataset)
- [Features](#features)
- [Dependencies](#dependencies)
- [Usage](#usage)
- [Model Training](#model-training)
- [Evaluation](#evaluation)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Overview

This project focuses on predicting the quality of red wine based on various chemical and sensory features. Wine quality is an essential factor for wine enthusiasts and producers, and accurate prediction can assist in producing high-quality wines.

## Dataset

The dataset used for this project can be found [here](https://archive.ics.uci.edu/ml/datasets/wine+quality). It includes various attributes of red wines, such as fixed acidity, volatile acidity, citric acid, residual sugar, chlorides, free sulfur dioxide, total sulfur dioxide, density, pH, sulphates, and alcohol, along with quality ratings.

## Features

The dataset comprises the following features:

1. Fixed Acidity
2. Volatile Acidity
3. Citric Acid
4. Residual Sugar
5. Chlorides
6. Free Sulfur Dioxide
7. Total Sulfur Dioxide
8. Density
9. pH
10. Sulphates
11. Alcohol

## Dependencies

To run this project, you will need the following Python libraries:

- Pandas
- NumPy
- Scikit-Learn
- Matplotlib
- Seaborn
- Jupyter Notebook (optional, for running the provided notebook)

You can install these dependencies using pip:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn jupyter
```

## Usage

1. Clone this repository to your local machine:

```bash
git clone https://github.com/Saquib34/RedWine-Quality-Prediction.git
cd red-wine-quality-prediction
```

2. Download the dataset from the provided link and place it in the `data` folder.

3. Open and run the Jupyter Notebook `wine_quality_prediction.ipynb` to explore the data, train the machine learning model, and make predictions.

## Model Training

In the Jupyter Notebook, you will find code for:

- Data preprocessing
- Model selection and training
- Hyperparameter tuning (if applicable)

Linear Regression ,Decision tree and Random forest are used for this prediction task, but you can experiment with different algorithms and techniques to improve the model's performance.

## Evaluation

The model's performance is evaluated using metrics such as accuracy, precision, recall, F1-score, and more. Detailed evaluation results can be found in the Jupyter Notebook.

## Results

The trained model accuracy can be seen in given ipynb fil, allowing you to predict the quality of red wines based on their chemical attributes.

## Contributing

Contributions to this project are welcome. You can contribute by:

- Opening issues to report bugs or suggest improvements.
- Forking the repository, making changes, and creating pull requests.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.