# deep-learning-challenge
# ANALYSIS REPORT
# The objective of this analysis is to build a neural network model that predicts if an applicant funded by AlphabetSoup would be successful or not
# The target variable for this model is the binary column IS_SUCCESSFUL
# The feature variables of the model are APPLICATION_TYPE, AFFILIATION	CLASSIFICATION, USE_CASE,	ORGANIZATION,	STATUS,	INCOME_AMT,	SPECIAL_CONSIDERATIONS, ASK_AMT
# Variables that were removed because they were neither a target or feature were EIN and NAME
# While evaluating what was best for the model, I tried many options
  # Tried 2, 3, and 4 layers
  # Tried many variations of neurons, from 5-100
  # Tried 3 activation functions: relu, tanh, sigmoid
  # Tried 3 optimizers: adam, RMSProp, SGD
# In all variations, I found the accuracy and loss to stay relatively the same, with the most optimal results in all my combinations being 73% accuracy and 55% loss.
# Therefore, I was unable to achieve the target performance of 75%
# In Summary, this model is not quite good enough to recommend for use on predicting success. This could be due to high randomness in success, or due to there being influential factors we did not have tracked in the dataset. To solve this classification problem, gathering more data could help.
