# Assignment 10 Data Bias Coding

## Hypothesis
The Perspective API will accuse comments that are not toxic of being toxic.

## Introduction
The Perspective API is a tool designed to help identify and flag toxic comments online. However, as with any algorithmic tool, there is a risk of bias. Bias can creep into machine learning models in a number of ways, such as biased training data or biased features used to build the model. In this project, we will explore whether the Perspective API is biased in a way that causes it to incorrectly flag non-toxic comments as toxic. We will be using sample data provided in class consisting of multiple comments and indications of their toxicity.

## Methods
To test our hypothesis, we will use the Perspective API to score a set of comments that we know are toxic and that we know are not toxic. We will then compare these scores to a threshold value that we determine based on the data we have. If the Perspective API flags a significant number of non-toxic comments as toxic, it suggests that the model may be biased.

## Results
Our results showed that the Perspective API did have higher toxicity indicators for non-toxic comments, but not enough to flag it as toxic based on our threshold. This suggests that the model is  biased but not to an extreme. Specifically, the model seemed to flag comments that contained certain ethnic groups or trigger words.

## Reflection
This project highlights the importance of testing machine learning models for bias. Even tools designed to combat online toxicity can themselves be biased, and it is important to be aware of these biases and work to address them. In this case, it is likely that the Perspective API was biased due to the way it was trained on a dataset that contained many comments with certain trigger words, leading the model to overgeneralize and flag more comments than it should. Moving forward, it will be important to continue to test and refine the Perspective API to ensure that it is both effective and fair.
