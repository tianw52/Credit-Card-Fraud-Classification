# Credit Card Fraud Binary Classification

A supervised learning model which detects credit card fraud. A binary classifier is trained to perform fraud detection analysis on a [credit card transaction dataset](https://www.kaggle.com/datasets/nelgiriyewithana/credit-card-fraud-detection-dataset-2023/data)

**Lastest version: binary fraud_final**

## Basic dataset info

The dataset we use is balanced. Each transaction is labeled as either fraudulent (1) or non-fraudulent (0)

<img width="339" alt="Screenshot 2023-11-07 at 02 14 45" src="https://github.com/tianw52/Credit-Card-Fraud-Classification/assets/129543727/c64e2b02-01fd-4999-9935-5a8b1be87d0b">

It has 31 columns, where 29 of them are features (v1-v28 and amount), class is the label.

<img width="381" alt="Screenshot 2023-11-07 at 02 16 02" src="https://github.com/tianw52/Credit-Card-Fraud-Classification/assets/129543727/7b1ef9fd-0fe9-4b0a-be00-cf7f9df93327">

## Training and testing sets

We use 80% of the data for training and validation, 20% for testing.

<img width="858" alt="Screenshot 2023-11-07 at 02 23 35" src="https://github.com/tianw52/Credit-Card-Fraud-Classification/assets/129543727/c5fa8d89-23a9-4eae-9825-5b6d2706fc0f">

## Model
We use a normalization layer to normalize the features first

<img width="405" alt="Screenshot 2023-11-07 at 02 25 32" src="https://github.com/tianw52/Credit-Card-Fraud-Classification/assets/129543727/0e7f2dce-236f-4b95-813b-1596c751ca7e">

Then we use a sequentail model with 4 activation layers. The input layer use He normal initializer, which is commonly used for Relu. The hidden layers use rectified linear (relu) activation function, output layer use sigmoid (logistic regression) which is commonly used in binary classification (the output is either 1 or 0).

<img width="612" alt="Screenshot 2023-11-07 at 12 19 43" src="https://github.com/tianw52/Credit-Card-Fraud-Classification/assets/129543727/eb732e1e-d5f8-4004-99c8-ad8072bf16cd">

## Results
<img width="612" alt="Screenshot 2023-11-07 at 12 20 25" src="https://github.com/tianw52/Credit-Card-Fraud-Classification/assets/129543727/6f480a1e-de8d-43af-ad2c-d2ec8190a875">

<img width="612" alt="Screenshot 2023-11-07 at 12 20 47" src="https://github.com/tianw52/Credit-Card-Fraud-Classification/assets/129543727/6072e4a6-e67b-4f9a-942f-462c3f8d8de0">

<img width="854" alt="Screenshot 2023-11-07 at 12 21 02" src="https://github.com/tianw52/Credit-Card-Fraud-Classification/assets/129543727/7395c6d6-92d6-49f7-95c3-ed49c812cd00">

A 96% accuracy was achieved.
