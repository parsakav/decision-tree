# Decision Tree Implementation from Scratch in Python

## 📌 Project Overview
This project provides a simple Python implementation of a Decision Tree classifier from scratch, specifically designed for discrete/categorical data. The implementation uses **Information Gain** as the splitting criterion to build the tree.

## 🌟 Key Features
- Pure Python implementation with no dependency on ML libraries
- Handles discrete/categorical features
- Uses **Information Gain** for optimal split selection
- Recursive tree construction
- Basic prediction functionality

## 📊 How It Works
1. **Tree Construction**:
   - Starts with the entire dataset at the root node
   - Calculates Information Gain for all possible splits
   - Selects the feature with maximum gain for splitting
   - Recursively builds subtrees for each branch

2. **Information Gain Calculation**:
   - Computes entropy of the target variable
   - Measures entropy reduction after splitting on each feature
   - Selects splits that maximize information gain

3. **Prediction**:
   - Traverses the tree based on feature values
   - Returns the majority class at leaf nodes
