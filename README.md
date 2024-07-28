# Car-Acceptability-Logistic-Regression

Introduction to the Car Acceptability Classification Database
The Car Acceptability Classification Database is derived from a hierarchical decision model initially developed to demonstrate DEX, an expert system for decision-making. The original work by M. Bohanec and V. Rajkovic, titled "Expert System for Decision Making," was published in Sistemica 1(1), pp. 145-157, 1990. This dataset serves as a practical illustration of evaluating cars based on various criteria and is widely used for classification tasks in machine learning.

Background and Purpose The primary purpose of this dataset is to evaluate cars according to a structured model that considers multiple attributes. The decision model simplifies complex evaluations by breaking them down into more manageable sub-decisions, following a hierarchical approach. This type of model is particularly useful in expert systems where decisions are made based on a set of rules derived from domain knowledge.

Dataset Description

The dataset comprises six features and one target variable:

1) Buying Price:

Represents the initial cost of the car. Possible values: vhigh (very high), high, med (medium), low.

2) Maintenance Price:

Represents the cost associated with maintaining the car. Possible values: vhigh, high, med, low.

3) Number of Doors:

Indicates the number of doors on the car. Possible values: 2, 3, 4, 5more.

4) Person Capacity:

Represents the maximum number of persons the car can carry. Possible values: 2, 4, more.

5) Size of Luggage Boot:

Describes the capacity of the luggage boot. Possible values: small, med, big.

6) Safety:

Indicates the safety level of the car. Possible values: low, med, high.

7) Car Acceptability (Target Variable):

Classifies the car based on the aforementioned features. Possible values: unacc (unacceptable), acc (acceptable), good, vgood (very good).

Concept Structure and Evaluation Criteria

The evaluation model assesses cars using a decision tree-like structure where each node represents a decision criterion. The final acceptability of a car is determined by the combined assessment of all criteria. Here’s an overview of the concept structure:

1) Price Evaluation:

Comprises Buying Price and Maintenance Price.

2) Capacity Evaluation:

Includes Number of Doors and Person Capacity.

3) Usability and Safety:

Considers Size of Luggage Boot and Safety.

Each feature contributes to the overall decision, influencing the car's classification as unacc, acc, good, or vgood. The hierarchical model ensures that all relevant aspects are taken into account, providing a comprehensive evaluation.

Objective

The primary objective of analyzing this dataset is to build a predictive model that can classify the acceptability of cars based on the given features. For this project, we will utilize a logistic regression model due to its effectiveness in binary and multiclass classification problems.

Source:

https://www.kaggle.com/datasets/subhajeetdas/car-acceptability-classification-dataset/data
