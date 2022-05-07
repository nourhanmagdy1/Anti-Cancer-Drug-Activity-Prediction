# Anti-Cancer-Drug-Activity-Prediction
This competition is a bioassay task for anticancer activity prediction, where each chemical compound is represented as a graph, with atoms representing nodes and bonds as edges. A chemical compound is positive against non-small cell lung cancer, or negative otherwise. Up to this point, you have learned various tricks and mechanisms to be used for building neural networks/tuning models.
# Model Tuning and Documentation:
Now based on the template, try to improve the model's performance on the public leaderboard by following the data science life-cycle for tuning. 
You can try different features, different hyperparameters/configurations of the model, and even a different model. 
For each trial, document the reason why you want to make the certain change and the expected outcome, before running the code. Record the observed performance and your thought on it. 
Recall that we have a DS life-cycle and we should know what to do when underfit/overfit. The final result is not important, but the process is. 
Documentation of your thought process is very important, since most people forgot why they test certain model/hyperparameter after they got the result (it takes time). 
It also helps a lot when you got stuck. 

**You can organize the notebook by listing**

thoughts and observations for trial 0, plan for trial 1
code for trial 1

thoughts and observations for trial 1, plan for trial 2
code for trial 2
…

# The tried solutions should cover at least:

GCN aggregation mechanisms: Tune at least three aggregation mechanisms (aka message_passing mechanisms) used in the graph convolution layer. 

Explain your understanding (based on the documentation/paper) of the mechanisms you chose.

Up-sampling: adjust the training data preparation/generation part to up-sample the positive class samples (very unbalanced dataset)


# Competition Link:
https://www.kaggle.com/competitions/cisc873-dm-f22-a6
