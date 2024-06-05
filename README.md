# Classification Models Comparison

## Summary of Findings

This project compares the performance of four different classification models—K-Nearest Neighbors (kNN), Logistic Regression, Decision Trees, and Support Vector Machines (SVM)—on a dataset related to the marketing of bank products over the telephone. The dataset, sourced from a Portuguese banking institution, includes results from multiple marketing campaigns aimed at predicting whether a client will subscribe to a term deposit.

### Key Findings:
- **K-Nearest Neighbors (kNN)**: Demonstrated moderate performance with balanced precision and recall. It's a straightforward model but may not be efficient for large datasets.
- **Logistic Regression**: Performed well with high precision and recall, making it a strong candidate for binary classification tasks. It also provides interpretability regarding feature importance.
- **Decision Trees**: Offered good interpretability and decent performance, though it may overfit if not properly tuned.
- **Support Vector Machines (SVM)**: Achieved high accuracy and was effective in finding the optimal hyperplane for classification. It's computationally intensive but performed well on this dataset.

### Actionable Insights:
- The model with the highest overall performance metrics (accuracy, precision, recall, and F1 score) should be considered for deployment.
- Hyperparameter tuning could further enhance model performance.
- Additional data preprocessing and feature engineering might improve predictive power.

### Recommendations:
- Collect more data to improve model robustness and generalization.
- Explore other classification algorithms and ensemble methods for potentially better performance.
- Regularly monitor the deployed model's performance and update it with new data as needed.

## Link to Notebook

[Classification Models Comparison Notebook](Classification_Models_Comparison.ipynb)

## Project Structure

- `PeeblesJ_Model_Comparison.ipynb`: Jupyter Notebook containing the data analysis, model training, evaluation, and comparison.
- `README.md`: This file providing an overview of the project, summary of findings, and link to the notebook.

## How to Run

1. Clone this repository.
2. Ensure you have the necessary Python libraries installed (pandas, seaborn, matplotlib, sklearn).
3. Open the Jupyter Notebook `PeeblesJ_Model_Comparison.ipynb`.
4. Replace the file path with the actual path to your CSV file if needed.
5. Run all cells to reproduce the results.

## Libraries Used

- pandas
- seaborn
- matplotlib
- scikit-learn

## Contact

For any questions or further information, please contact James Peebles at Jamesewpeebles@gmail.com.
