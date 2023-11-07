# Credit Card Fraud Classification

A supervised learning model which detects credit card fraud. A binary classifier is trained to perform fraud detection analysis on a [credit card transaction dataset](https://www.kaggle.com/datasets/nelgiriyewithana/credit-card-fraud-detection-dataset-2023/data)

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

Then we use a sequentail model with 4 activation layers !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!! NEED INPUT

<img width="405" alt="Screenshot 2023-11-07 at 02 24 58" src="https://github.com/tianw52/Credit-Card-Fraud-Classification/assets/129543727/22648e79-d763-4639-b64e-d4fc8e150b16">

## Results
<img width="629" alt="Screenshot 2023-11-07 at 02 22 29" src="https://github.com/tianw52/Credit-Card-Fraud-Classification/assets/129543727/e4941183-eff1-4b90-9616-09a5b494bff0">

<img width="629" alt="Screenshot 2023-11-07 at 02 22 49" src="https://github.com/tianw52/Credit-Card-Fraud-Classification/assets/129543727/f26bf54c-0f37-47f5-ba92-bd8fd951c7a4">

<img width="858" alt="Screenshot 2023-11-07 at 02 23 15" src="https://github.com/tianw52/Credit-Card-Fraud-Classification/assets/129543727/a61512f8-d89e-434f-9920-26d21c3d3583">
