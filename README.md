SMS Spam Detection Using Lasso Regression
         This project focuses on building an SMS Spam Detection system using machine learning techniques. The goal is to classify messages as spam or ham by converting text data into numerical features using TF-IDF.

Steps Involved in the Project:-
Load Dataset :
   * Import the SMS dataset containing messages labeled as spam or ham.
Data Preprocessing :
   * Select required columns and convert labels (ham = 0, spam = 1).
Text Vectorization (TF-IDF) :
    * Convert SMS text into numerical features using TF-IDF.
Feature Count :
    * Calculate the total number of features generated.
Split Dataset :
    * Divide data into training and testing sets.
Apply Lasso Regression :
     *Train the model using Lasso (alpha = 0.1) to perform feature selection.
Analyze Coefficients :
    *  Count non-zero (selected) and zero (eliminated) features.
Compare Alpha Values :
     * Train with different alpha values (0.01, 0.1, 1) and compare selected features.
Calculate Feature Reduction :
     * Compute percentage reduction in features after applying Lasso.
