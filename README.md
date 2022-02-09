# Toxic_comment_NLP
Predict toxicity of comment


I have implemented a model to predict the toxicity of comments between 0 and 1. 

The dataset contains 45 features and I performed exploratory data analysis on them.

I divided features in gender, religion, and user feedback and try to find the percentage of additional toxicity features like an insult, obscene, threat, etc.

I used count and TF-IDF method for vectorization and build SGD regressor and decision tree model, found MSE 0.023 with the SGD regressor and TF-IDF vectorization
