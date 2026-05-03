Part I: Data Preparation
In this project, you will use https://www.kaggle.com/datasets/geadalfa/cracked-non-crackedsurface-datasets/data Classification dataset
You can use keras/tensorflow/pyTorch or write your own routines.
1) First, download the data file, load it, and
2) Describe the data
3) Visualize the data using proper visualization methods.
Part II: Training the models
In this project, you need to implement 3 models (FFNN, RNN (LSTM), and
CNN) which will be used to classify the data in Part I. Use the appropriate
hyperparemeters for each model in order to get the highest accuracy.
You also need to write the training function (training), and should explore the
following hyperparameter settings:
• Batch size: Number of examples per training iteration.
• Number of layers: Try using different number of layers in your model and
compare the performances.
• Dropout is an effective strategy to defend against overfitting. Try using
different dropout rate to compare the performances.
• Optimizer: Try using different optimizers such as SGD, Adam, RMSProp.
• Regularization (weight decay): L2 regularization can be specified by setting
the weight_decay parameter in optimizer. Try using different regularization
factor and check the performance.
• Learning rate, Learning rate scheduler: Learning rate is key hyperparameter in
model training, and you can gradually decreasing the learning rate to further
improve your model. Try using different learning rate and different learning rate
scheduler to compare the performance.
You could analyze one hyperparameter at a time (i.e. fixing all others to some
reasonable value), rather than performing grid search.
To evaluate the performance of trained models, you also need to write a function
(evaluation) which loads the trained model and evaluate its performance on
train/test set. In your report, please clearly state what hyperparameters you
explored, and what accuracy the model achieved on train/test set.
Deliverables:
• Documentation (PDF file) which includes the problem definition, screenshots
of the code, screenshots of the output, visualization of the accuracy change, the
description of hyperparameters used in each model, full analysis of your results.
• A notebook file (ipynb) 

note please add the data like this 
<img width="237" height="221" alt="image" src="https://github.com/user-attachments/assets/d3df4337-ecd6-48d3-8a0a-11ec87727b09" />
