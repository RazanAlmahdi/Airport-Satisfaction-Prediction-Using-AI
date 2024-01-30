# Airport Satisfaction Prediction

<!--Title-->
## Purpose
<!--Purpose of the project-->
The aim of this initiative is to create robots that can aid travelers during their airport waiting
time. These robots will possess cutting-edge sensors and scanners, such as facial recognition
technology, passport and barcode scanners, and a high-quality display for presenting up-to-date information. This project seeks to develop a model capable of forecasting passenger satisfaction using
various data points gathered through airport questionnaires. By taking into account factors
such as gender, age, ticket class, customer loyalty, and whether the trip is for business or
personal reasons, this model will aid in improving our robot’s performance to better cater to
passengers’ needs.

<img src="https://github.com/AichaSidiya/FileProcessing/blob/main/demoFiles.gif"/>

<!--Header 2 description of the project-->
## Description

<p style="text-align: justify">
The model was trained using data from a survey about airline satisfaction that was collected
on Kaggle.To clasify user satisfaction we worked on 3 models and analysed the differences between them to determine the most efficent one. These include Linear Regression, SVM, and
NN.The logistic regression model exhibited a higher
number of false positives and false negatives.
This suggests that the model may not be effective at accurately predicting
satisfaction levels. While the SVM and NN models exhibited
higher true positive and true negatives values. After evaluating the models, we determined
that the SVM and neural network models were the most effective, with both
achieving nearly 96% accuracy and demonstrating similar ROC curves, while being more efficent then NN.

## Built With
* Python

<!--Header 3 installation and launching the project-->
## How to run the program
* Clone the repository to your local machine:
```
git clone https://github.com/AichaSidiya/AirportSatisfactionPrediction.git
``` 
* Run on [Google Colab](https://research.google.com/colaboratory/)


## Authors
<!-- The contributors to the project-->
* [Aicha Sidiya](https://github.com/AichaSidiya)
* [Razan Almahdi](https://github.com/RazanAlmahdi)


## Acknowledgments
<!-- Insparation files, codes, and general refrences used in writing the code of the project-->
* [Data Acquisation and Exploration](https://www.kaggle.com/code/adityan1123/airline-passenger-satisfaction)
