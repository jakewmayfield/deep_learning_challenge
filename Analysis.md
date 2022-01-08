# Alphabet Soup Charity Neural Network Analysis

## Overview
This analysis serves to explore the creation, and optimization of a deep learning neural network that was used to classify if an organization would be successful if funded by Alphabet Soup Charity.

## Results
Four total attempts were made to attempt to train the model to 75% or higher, to no avail.  It appears that model saturation was achieved around 72%, as no model performed better than 73% or worse than 72%.

* Data Preprocessing
    * The variable used for the target of the model was "IS_SUCCESSFUL".  This was historical data that listed if an organization was successful after funding.
    * The features of the model were everything else, except for the columns "EIN", "NAME".  During optimization additional columns were dropped ("SPECIAL_CONSIDERATIONS").
* Compiling, Training, and Evaluating the Model
    * In the beginning of the model, I used 2 hidden layers with 50 and 25 features, and 20 epochs to avoid overcrowding.
    * On my second-fourth attempt I added another layer, increased features to 100, 50, and 40 (all with relu), and increased epochs to 50 and then 100.

## Summary
Overall, the model performed fairly well, with saturation occuring around 72%.  Another model with cleaner data, and using a different encoding method would help the model to perform better.
