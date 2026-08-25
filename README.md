# Random-Forest-vs-XGBoost
Ensemble Learning


## Model Comparison: Single vs. Ensemble Methods

| Model | Accuracy | Precision | Recall | F1-Score |
| :--- | :--- | :--- | :--- | :--- |
| **Decision Tree (Single)** | 0.7765 | 0.7206 | 0.7101 | 0.7153 |
| **Random Forest (Bagging)** | 0.8101 | 0.7727 | 0.7391 | 0.7556 |
| **XGBoost (Boosting)** | **0.8268** | **0.8030** | **0.7681** | **0.7852** |

### Key Takeaways:
- **Feature Importance Shift**: Random Forest distributes importance across continuous features like `Fare` and `Age`, whereas XGBoost places heavy emphasis on strong binary discriminators like `Sex_male`.
- **Performance Uplift**: Ensembles outperform the single Decision Tree baseline by mitigating overfitting and combining weak learners.
