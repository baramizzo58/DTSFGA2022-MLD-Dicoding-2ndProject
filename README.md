# DTSFGA2022-MLD-Dicoding-Development-1stProject
1st Project of Machine Learning Developer (Learn Machine Learning Development Stage) Training in Fresh Graduate Academy Program (Digital Talent Scholarship 2022).

## Project explanation:
Creating Natural Language Processing Models with TensorFlow.

## Dataset:
Using `amazon_cells_labelled1.txt` data that consist of 2001 rows × 2 columns

## Data Preparation
Using train test split with splitting ratio 80:20.

## Modeling
* Using library `Tokenizer` from `tensorflow.keras.preprocessing.text`
* Using library `pad_sequences` from `tensorflow.keras.preprocessing.sequence`
* Threshold: 90% in validation accuracy.

## Result
* Epoch: 12/30
* accuracy: 0.9087
* val_loss: 0.3017
