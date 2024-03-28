# DS_Hw7
This code is written in Python and performs collaborative filtering-based recommendation using the Surprise library. Here's a breakdown:

1. **Installation**: It installs the `scikit-surprise` library, which is used for building and analyzing recommender systems.

2. **Imports**: It imports necessary libraries including pandas for data manipulation and Surprise for recommendation algorithms and evaluation.

3. **Dataset Loading**: It loads the MovieLens dataset (`ml-100k`) from Surprise's built-in datasets.

4. **Data Preprocessing**: It converts the raw data into a pandas DataFrame for easier manipulation and visualization.

5. **Model Initialization**: It initializes three different recommendation models: SVD, SVD++, and NMF.

6. **Cross-validation**: It performs cross-validation on each model to evaluate their performance using RMSE and MAE metrics.

7. **Hyperparameter Tuning**: It uses GridSearchCV to search for the optimal hyperparameters for the SVD model.

8. **Model Training**: It trains the SVD model with the best hyperparameters on the entire dataset.

9. **Prediction**: It generates predictions for all user-item pairs and prints them.

10. **Note**: The last comment advises against running the prediction loop, possibly due to its potentially large output.

Overall, the code demonstrates the process of building, evaluating, and tuning collaborative filtering recommendation models using Surprise in Python.