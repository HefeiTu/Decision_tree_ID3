# Decision Tree

Python and NumPy implementation of ID3 algorithm for decision tree. This is a vectorized implementation of the Decision tree tutorial code by Google Developers.

> Youtube: https://www.youtube.com/watch?v=LDRbO9a6XPU

> Reference: https://github.com/random-forests/tutorials/blob/master/decision_tree.ipynb

### Input format

1) The algorithm expects the first N-1 columns to be features and the last column to be labels.
2) The code was written for a subset of the [Wine quality dataset](https://archive.ics.uci.edu/ml/datasets/wine+quality).

### Hyperparameters

1) **Depth** : Pre-pruning depth of decision tree.
2) **min_sample_split**: Minimum number of samples to be present at a node for further splits to occur.

### Search for best attribute to split

1) For numerical attributes, the algorithm iterates over all values in a column to find the best value. (Binary split)
2) For categorical attributes, each split considers if a particular sample belongs to a particular category or not. (Binary split)
