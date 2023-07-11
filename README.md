# UFC-Betting-Algorithm
This project aims to predict the outcome of UFC fights using machine learning techniques. The data used in this project was obtained from a publicly available repository, which was then cleaned and preprocessed to prepare it for analysis. The cleaned dataset was split into training, validation, and test sets to train and evaluate various machine learning models.

# Dataset
The initial dataset used in this project was sourced from an external GitHub repository. It contains information about UFC fights, including fighter statistics, fight details, and fight outcomes. The dataset was cleaned by removing irrelevant columns, handling missing values, and encoding categorical variables appropriately. Additionally, feature engineering techniques were applied to derive meaningful features that could potentially improve model performance.

# Machine Learning Models
To predict the outcomes of UFC fights, this project explores several machine learning models available in the scikit-learn (SKlearn) library. The models considered include random forest, logistic regression, and K-nearest neighbors (KNN). These models were trained on the training set and evaluated on the validation set to assess their performance.

# Model Selection
After evaluating the performance of various machine learning models, a gradient boosted model was selected as the final predictive model. The gradient boosted model demonstrated superior performance compared to other models in terms of accuracy and predictive power. To further optimize the model's performance, the Optuna package was employed for hyperparameter optimization.

# Algorithm for Betting
In addition to predicting fight outcomes, this project includes an algorithm that incorporates the final machine learning model to make betting decisions. The algorithm allows for betting on either the blue fighter or the red fighter, or choosing not to bet at all if the risk is deemed too high. The algorithm's risk tolerance is tunable, allowing users to adjust the level of risk they are willing to take.

# Performance Evaluation
The performance of the betting algorithm was evaluated using the test set, which contained 286 potential bets. The baseline accuracy of the algorithm, considering all potential bets, was found to be 82%. However, by filtering out the risky bets based on the algorithm's risk tolerance, the accuracy increased significantly to 94%. This demonstrates the algorithm's ability to make informed betting decisions and achieve higher accuracy by avoiding risky bets.

# Conclusion
The UFC Fight Predictor project showcases the process of predicting fight outcomes using machine learning techniques. By leveraging a cleaned and preprocessed dataset, along with various SKlearn models, a gradient boosted model was selected as the best performer. The Optuna package was utilized for hyperparameter optimization, resulting in improved model performance. The algorithm incorporating the final model demonstrates the ability to make betting decisions with high accuracy, while allowing for customizable risk tolerance.
