# Custom_Ensemble

Ensmeble methods allow to use more than one estimators to make a prediction.

Example: Random Forest, where it trains multiple decision trees to give a prediction, which is averaged. The prediction made becomes a feature while making the final prediction.

Generally, an ensmeble method involves the RandomTree estimator. The aim of this repository is to create a custom ensemble method comprising of customized estimators of our choice. 

The methodoly follows as:

1. Creating a custom class consisting of base estimator and TransformerMIxin not to predict, but to decide which prediction becomes feature in our final prediction.

2. Creating a pipeline of a). Decision trees b) KNN

3. Combining the predictions of both into a single feature matrix

4. Using this, into making the final prediction and getting the score.
