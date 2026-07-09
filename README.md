## Project 1: Titanic Survival Prediction (`work1.ipynb`)

###  Project Overview
Built a classical machine learning binary classification pipeline to predict passenger survival on the Titanic dataset. The target variable `Survived` is categorical ($0$ or $1$).

###  Data Preprocessing & Engineering
* **Data Cleaning:** Identified and handled missing values appropriately (e.g., imputing missing values using the **mode**).
* **Feature Selection:** Dropped irrelevant text and identification columns that do not contribute predictive power to the model.
* **Data Splitting:** Applied `train_test_split` to create pristine training and testing sets to evaluate generalization.

###  Models Evaluated & Hyperparameter Tuning
Evaluated three core classification architectures to compare performance:
1.  **Logistic Regression** (Baseline statistical model)
2.  **Decision Tree Classifier** 3.  **Random Forest Classifier** (Ensemble method)

* **Optimization:** Compared initial training and testing accuracies to diagnose underfitting/overfitting, followed by **Hyperparameter Tuning** to fine-tune the decision boundaries.

###  Final Results
* **Best Model:** **Random Forest Classifier** outperformed both Logistic Regression and the standalone Decision Tree.
* **Conclusion:** The ensemble nature of the Random Forest successfully reduced variance, yielding the highest testing accuracy on the unseen test data.

## CREATING AN NLP MODEL
## SPAM  DETECTION MODEL
in this model the dataset consists of all the emails which are sent to the user on a daily basis this model uses multinomial bayes classifier theorem to predict
whether the message sent is legitimate or not.
## WORKNG
the model analyses the data by splitting the data based on sentiment SPAM=0,HAM=1,
the data is preprocessed and splitted into tokens.
later the tokens and combined and are vectorised using tfidf vectorizer.
finally the model is trained and tested over sample data givenm by user to predict the output.
## FINAL
this model helps in understanding how the data is splitted and vectorized to give accurate predicitions.
