# Decision-Tree-on-Iris-Dataset
This segment of code deals with understanding how decision trees work using the Iris Dataset and try to build a model for decision tree, train the model and find the decision boundary.<br>
First, load the Iris Dataset, which contains the data(data to learn), target(classification labels), target_names(meaning of the labels), feature_names(meaning of the features) and DESCR(full description of the dataset).<br>
Once loaded, we explore the dataset to analyze its dimensionality, classes and features.<br>
Then, plot the dataset using matplotlib to visualize the dataset.<br>
Next, to understand the interaction of dimensions, we plot the first three PCA dimensions.
Now, create a DecisionTreeClassifier model, using the iris.data, iris.target and train the model.
Perform cross-validationto evaluate performance of the model.
Next, plot the decision surface of the decision tree using paired features.
Finally,optimize the decision tree and detect potential over-fitting.
Plot the final results.
