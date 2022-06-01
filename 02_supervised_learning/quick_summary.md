# Quick Summary of when to use each model

### Nearest Neighbors
- For small datasets, good as a baseline, easy to explain

### Linear Models
- Go-to as a first algorithm to try, good for very large datasets, good for very high-dimensional data

### Naive Bayes
- Only for classification. Even faster than linear models, food for very large datasets and high-dimensional data. Often less accuracte than linear models

### Decision trees
- Vary fast, don't need scaling of the data, can be visualized and easily explained

### Random forests
- Nearly always perform better than a single decision tree, very robust and powerful. Don't need scaling of data. Not good for very high-dimensional sparse data

### Gradient boosted decision trees
- Often slightly more accuracte than random forests. Slower to train but faster to predict than random forests, and smaller in memory. Need more parameter tuning than random forests.

### Support vector machines
- powerful for medium-sized datasets of features with similar meaning. Require scaling of data, sensitive to parameters.

### Neural Networks
- Can build very complex models, particularly for large datasets. Sensitive to scaling of the data and to the choice of parameters. Large models need a long time to train.


## Good Habits
- start with a simple model, such as linear model or naive Bayes or nearest neighbors classifier before moving to a more complex model
