# Apple Quality Classification

## Authors

- Andrea Falbo ([GitHub](https://github.com/LilQuacky))
- Damiano Pellegrini ([GitHub](https://github.com/DamianoPellegrini))
- Ruben Tenderini ([GitHub](https://github.com/Ruben-2828))

## Synopsis

ML-Apple-Quality is a demonstration project created for the Machine Learning course at the University of Milano-Bicocca. 
The purpose of this project is to develop and evaluate machine learning models 

## Project Overview

This repository contains a machine learning model designed to classify apples based on their quality. The model predicts whether an apple is good or bad based on features such as size, weight, sweetness, crunchiness, juiciness, ripeness, and acidity.

## Files in the Repository

- **apple_quality.csv** - The dataset containing 4000 apple observations with labeled quality.
- **Progetto_ML.ipynb** - Jupyter Notebook containing the implementation of the machine learning model.
- **presentazione.pdf** - A presentation explaining the model development process and results.
- **relazione.pdf** - A detailed project report outlining dataset design, exploratory data analysis, model selection, and evaluation.

## Dataset Description

The dataset consists of 4000 samples with the following features:

- **Size**: Apple size (scaled values between -7.15 and 6.41)
- **Weight**: Apple weight (-7.15 to 5.79)
- **Sweetness**: Level of sweetness (-6.89 to 6.37)
- **Crunchiness**: Texture/crunchiness (-6.06 to 7.62)
- **Juiciness**: Level of juiciness (-5.96 to 7.36)
- **Ripeness**: Ripeness level (-5.86 to 7.24)
- **Acidity**: Acidity level (-7.01 to 7.4)
- **Quality**: Target variable with two possible values: "good" or "bad"

## Machine Learning Models Used

Three different classification models were implemented and compared:

- **Support Vector Machine (SVM)** - Implemented using the RBF kernel.
- **Naive Bayes (GaussianNB)** - A probabilistic model assuming feature independence.
- **Multi-Layer Perceptron (MLP)** - A neural network with three hidden layers.

## Model Performance

The models were evaluated using accuracy, precision, recall, and F1-score. The results are as follows:

- **MLP**: Best performance with 93% accuracy.
- **SVM**: Second-best performance with 91% accuracy.
- **Naive Bayes**: Lowest performance with 75% accuracy.

## Running the Model

Execute the Jupyter Notebook **Progetto_ML.ipynb** to train and evaluate the model:

```bash
jupyter notebook Progetto_ML.ipynb
```

## License

This project is licensed under the MIT License.
