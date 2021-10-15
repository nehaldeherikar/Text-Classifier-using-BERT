# Text-Classifier-using-BERT

Tools - Python, Pandas, Amazon S3, Amazon SageMaker Pipelines, Amazon SageMaker Feature Store.

Method - Natural Language Processing using BERT, ML Pipelines and MLOps.

Description - Build a SageMaker Pipeline to train and deploy a BERT-Based text classifier to predict the
sentiment for each customer review.
  
1. Defined and run a pipeline using a directed acyclic graph (DAG) with specific pipeline parameters and model hyper-parameters
2. Defined a processing step that cleans, balances, transforms and splits our dataset into the train, validation, and test dataset
3. Defined a training step that trains a model using the train and validation datasets
4. Defined a processing step that evaluates the trained model's performance on the test dataset
5. Defined a register model step that creates a model package from the trained model
6. Defined a conditional step that checks the model's performance and conditionally registers the model for deployment.


This Project is part of Practical Data Science Specialization offered by AWS & DeepLearning.AI on Coursera
