# Deep Learning Challenge

## Background
In this challenge I build a neural network that helps determine if applicants will be successful if funded by the organization Alphabet Soup.  There's a provided CSV with metadata on 34,000 organizations that I use for training the model.

## Steps
### Preprocessing
I dropped non-pertinent columns, created bins for rare data, and converted categorical data with get_dummies.

### Creating the Model
I used TensorFlow to build the neural network.  And over 4 total attempts I adjusted columns in original data, changed number of features in hidden layers, added more hidden layers, tweaked epoch size, and experimented with different optimizers.


## Results
No model every acheived above 73%, but lower than 72%.  It seems that this data has reached its saturation point around 72% and without drastically changing the provided data, the model can't learn more.
