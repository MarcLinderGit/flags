# Flag Classification Decision Tree
### Project Overview

**Objective:** This project aims to develop a decision tree model to classify countries' continent ("landmass regions") based on flag characteristics. The primary goal is to predict whether a country belongs to either Europe or Oceania based on flag attributes.

**Data Source:** [Flag dataset](https://archive.ics.uci.edu/dataset/40/flags)

### Tasks Summary

Here's an overview of the tasks conducted using Python and various libraries:

1. **Exploratory Data Analysis (EDA) and Decision Tree Creation:** I'll begin by exploring the dataset and checking the distribution of landmass categories (Europe and Oceania). Then, I'll construct a decision tree model using Scikit-Learn for country classification.

2. **Data Visualization:** I'll create visualizations to understand the relationships between predictor variables and visualize the decision tree structure.

3. **Data Preprocessing:** Data will be preprocessed by selecting relevant predictor variables and encoding categorical features.

4. **Data Splitting and Decision Tree Fitting:** The dataset will be split into training and testing subsets. Subsequently, I'll fit a decision tree classifier and evaluate its accuracy.

5. **Hyperparameter Tuning:** Hyperparameters of the decision tree, specifically maximum depth and complexity cost parameter (ccp_alpha), will be optimized to enhance model performance.

6. **Pruning the Decision Tree:** Different values of ccp_alpha will be experimented with to prune the decision tree, improving its generalization ability.

7. **Visualization of the Final Decision Tree:** I'll provide a visualization of the final decision tree, showcasing the optimal hyperparameters.