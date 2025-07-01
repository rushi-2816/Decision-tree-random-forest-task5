# Task 5 – Decision Trees & Random Forests

## 🎯 Objective
Build and compare Decision Tree & Random Forest models for classification.

## 📁 Dataset
- `heart.csv` from [Kaggle](https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset)

## ✅ Work Done
- Trained Decision Tree and visualized it
- Controlled depth to avoid overfitting
- Trained Random Forest and compared accuracy
- Plotted feature importances
- Used cross-validation for evaluation

## 📊 Results
- Decision Tree Accuracy: ~84%
- Random Forest Accuracy: ~89%

## ❓ Interview Questions (Short Answers)

1. **How does a decision tree work?**  
   Splits data based on feature conditions to classify samples.

2. **What is entropy & information gain?**  
   Entropy: impurity measure. Info gain: reduction in entropy after split.

3. **Why is random forest better?**  
   Combines multiple trees → less overfitting, better accuracy.

4. **What is overfitting?**  
   Model memorizes data. Prevent by limiting depth or using ensembles.

5. **What is bagging?**  
   Training on random samples and combining results.

6. **How to visualize a tree?**  
   Using `plot_tree()` or Graphviz.

7. **Feature importance?**  
   Shows which features help most in decision-making.

8. **Pros/Cons of Random Forest?**  
   ✅ Accurate, stable  
   ❌ Slower, harder to interpret
