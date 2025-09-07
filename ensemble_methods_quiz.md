# Ensemble Methods Quiz

## Questions

### 1. Which of the following best describes the main idea of ensemble methods?
- A) Train one strong model to make predictions
- B) Combine multiple weak or strong models to improve performance
- C) Use only decision trees for predictions
- D) Reduce the size of the dataset to speed up training

**Answer:** B  
**Explanation:** Ensemble methods combine multiple models to reduce variance, bias, or improve predictions.

### 2. Bagging is primarily used to:
- A) Reduce bias
- B) Reduce variance
- C) Increase dataset size
- D) Reduce feature dimensions

**Answer:** B  
**Explanation:** Bagging trains multiple models on random samples and averages predictions to reduce variance.

### 3. Which of the following is a characteristic of Random Forests?
- A) Uses boosting on weak learners
- B) Uses a single decision tree with depth 1
- C) Combines many decision trees using bagging and feature randomness
- D) Only works for regression problems

**Answer:** C  
**Explanation:** Random Forests train multiple trees on bootstrapped samples and random feature subsets to reduce correlation and overfitting.

### 4. Boosting methods primarily aim to:
- A) Reduce variance
- B) Reduce bias
- C) Reduce training time
- D) Increase the number of features

**Answer:** B  
**Explanation:** Boosting sequentially trains models focusing on previous errors, reducing bias.

### 5. Which of the following statements is true about AdaBoost?
- A) It combines models in parallel
- B) It assigns equal weight to all samples
- C) It increases the weight of misclassified samples for the next learner
- D) It cannot be used for classification problems

**Answer:** C  
**Explanation:** AdaBoost increases the weight of misclassified samples so that the next learner focuses on them.

### 6. In Stacking, the meta-model is trained using:
- A) The original dataset only
- B) Predictions from the base models
- C) Random noise added to data
- D) Bootstrap samples

**Answer:** B  
**Explanation:** Stacking trains a second-level model on base model predictions to learn the best combination.

### 7. Blending differs from stacking in that:
- A) Blending uses a holdout set for meta-model training
- B) Blending uses cross-validation folds
- C) Blending cannot combine different model types
- D) Blending reduces variance instead of bias

**Answer:** A  
**Explanation:** Blending uses a separate holdout set to train the meta-model, unlike stacking which uses cross-validation.

### 8. Which ensemble method is most likely to overfit if base learners are too complex?
- A) Bagging
- B) Random Forest
- C) Boosting
- D) None of the above

**Answer:** C  
**Explanation:** Boosting focuses on errors, so strong base learners may overfit the training data.

### 9. What is the primary advantage of Random Forest over a single decision tree?
- A) Faster training time
- B) Handles missing data automatically
- C) Reduces overfitting by averaging multiple trees
- D) Requires fewer features

**Answer:** C  
**Explanation:** Averaging many trees reduces variance and overfitting compared to a single tree.

### 10. Which of the following is a disadvantage of Bagging?
- A) It increases bias significantly
- B) It requires sequential training
- C) It may not reduce bias if the base learners are weak
- D) It cannot be used for regression

**Answer:** C  
**Explanation:** Bagging reduces variance, but cannot fix high bias from weak base learners.

### 11. How does AdaBoost assign importance to base learners in the final model?
- A) By the training error of each learner
- B) Equally for all learners
- C) Randomly
- D) Based on the number of features used

**Answer:** A  
**Explanation:** Learners with lower error get higher weight in the final prediction.

### 12. Which of the following is true about stacking with diverse base models?
- A) It usually performs worse than homogeneous models
- B) Diversity among base models often improves ensemble performance
- C) Base models must be of the same type
- D) It is equivalent to bagging

**Answer:** B  
**Explanation:** Diverse base models make different errors, which the meta-model can combine effectively.

### 13. Which ensemble method can be used for both classification and regression?
- A) AdaBoost
- B) Bagging
- C) Random Forest
- D) All of the above

**Answer:** D  
**Explanation:** Bagging, Random Forest, and Boosting can all be applied to classification and regression.

### 14. Why is feature randomness important in Random Forest?
- A) It increases the depth of trees
- B) It reduces correlation among trees, improving ensemble accuracy
- C) It speeds up the training
- D) It reduces bias

**Answer:** B  
**Explanation:** Random feature selection reduces correlation among trees, enhancing generalization.

### 15. Which of the following is true regarding Blending?
- A) It requires k-fold cross-validation like stacking
- B) It uses a separate holdout set to train the meta-model
- C) It trains all base models sequentially on misclassified samples
- D) It cannot combine different model types

**Answer:** B  
**Explanation:** Blending trains base models on the training set and uses a holdout set for the meta-model.

