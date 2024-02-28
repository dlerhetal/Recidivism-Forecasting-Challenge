# Recidivism Prediction Project README
Team Members: William Brewer, Dale Linn, Kiara Shannon, Hugo Troche

## Overview

This project develops a deep learning model to predict recidivism within 3 years, inspired by the National Institute of Justice's Recidivism Forecasting Challenge. It aims to refine recidivism forecasts using both person- and place-based variables to aid community supervision and reintegration efforts.

## Dataset

The dataset includes various features relevant to recidivism, processed and encoded for model training. Specific details on dataset composition are documented within the notebook.

## Model

A deep neural network with two hidden layers is employed, optimized with the Adam optimizer and binary crossentropy loss function. The model aims for high precision and recall in predicting recidivism.

## Results

The model achieved an accuracy of approximately 92.785% on the test set, with detailed performance metrics including precision, recall, and F1 score provided in the confusion matrix analysis.

## Conclusion

The project demonstrates the potential of deep learning in enhancing recidivism prediction, aligning with the goals of the NIJ's challenge to improve public safety and justice outcomes.

For more information on the challenge that inspired this project, please visit the [NIJ's Recidivism Forecasting Challenge page](https://nij.ojp.gov/funding/recidivism-forecasting-challenge).

---
In creating this model we extensively used class materials, google-copilot and chat gpt. We also cross referenced results with submissions to the NIJ challenge which can be found here:https://nij.ojp.gov/funding/recidivism-forecasting-challenge-results
