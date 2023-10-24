# Predicting diabetes

This projects purpose was to learn how to deal with multiple problems common in the machine learning problems, in particular medical problems, such as:

1. inbalanced targets
2. Not enough samples
3. Model evaluation (precision vs recall vs … ) in medical problems

Both under sampling and oversampling were tried in order to combat the first two issues, which were build in custom preprocessing pipelines (see Input 7-9 in the code). A range of models were then applied and evaluated using different metric sand k-fold cross-validation (starting from input 22 in the code). In addition, GridSearch was applied to determine best parameters for some of the most promising models like ensemble models. During evaluation I realised that some of the data is fraudulent, which would have required a new iteration of the approach to identify and remove this data. This would lead to improvement of overall scores. More detailed commentary can be found in the code itself, although in German.
