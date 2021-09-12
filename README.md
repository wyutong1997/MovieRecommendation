# MovieRecommendation

## Data set
Use Movie Lens data set.

## Feature Selection
### Useful Features:
For this scenario, user rating history and movie features are useful to this recommendation task. The useful movie features will be movie genres, movie release year, movie rating history. The useful users features will be the genres of movie he watched recently, realease year of movies he watched, ppsitive rating history.
### Feature Extract
Extract user features and movie features by pandas and then concatenate them together to a single .csv file. Use Sk-learn to split trainning, testing data.

## Build Model
Build a deep learning model by Tensorflow which imitated the architecture of Wide and Deep Model. 

## Model Evaluate
Draw ROC and PR curve, the final accuracy of this model is 80% on test set
