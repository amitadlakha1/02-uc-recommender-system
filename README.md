# use-case-recommender-system

Design solution architecture for deploying / Implementing a recommendation engine to generate product recommendations based on clickstream data

##### Assume:

- the data scientist has built the first version of the model on a jupyter notebook using clickstream data processed as part of 01-uc-bigdataprocessing
- the model is required to be deployed in a production setup for continous training and scoring on a daily basis
- the model needs be expanded to multiple geo regions
- the model outputs should be available in both offline and online mode (real-time prediction service)

##### For you to decide:

- AWS services to use (except Sagemaker, Personalize)
- MLOps strategy

##### Have in mind:

- to be implemented on AWS stack
- we are not looking at the modelling approach but more interested in deploying and running the recommendation engine in a scalabale manner 
- the model prediction service has to scale for millions of users

##### Output expected

- the output should show the deployment and the Implementation view as design document with all core architecture considerations and components. 