# Simmilar/Dissimilar Question Pairs
This is a project developed using machine learning technique called NLP(Natural Language Processing) where in one can find out whether the two given statements are duplicate/having same meaning or different. The Data-set used is from Kaggle(quora case). This process of finding out duplicate question pairs is helpful in reducing the amount of time spent to answer same/similar questions and bringing all the people who want to know answers to similiar questions at one place by merging them without creating any confusion.
The overall project required-
1. Importing requirements and dataset
2. Defining the Pre-Process Function which included Lemmatization,demojization,decontraction etc.
3. Feature Engineering
4. Studying some advanced features like fuzzy features
5. Hyper-parameter tuning
6. Checking accuracy on RandomForest and XGBoost Classifier

I also had plans to  deploy this on local host website using Pycharm and Heroku but there was some issue regarding authentication hence I couldn't, so here in this repository I have the jupyter notebook to the code. 

I achieved an accuracy of 79.91% using my model while on RandomForestClassifier, while training on 50,000 amount of data. Some other models have that had the best accuracy were around 85%.
Here is the link of paper for your reference- https://arxiv.org/ftp/arxiv/papers/2004/2004.11694.pdf
