# Task 01 — Prediction Analysis

## Objective
Understand how the model predicts digits and why some predictions are correct or wrong.

## Results
The model predicted most samples correctly.
Some mistakes happened when digits looked similar.

## Analysis
The image is flattened and passed to a Dense layer with ReLU.
ReLU helps the model learn important features.
Softmax gives probabilities for each digit.
Adam optimizer helps the model train in a stable way.

## Key Takeaway
The model works well when test images are similar to training images.
