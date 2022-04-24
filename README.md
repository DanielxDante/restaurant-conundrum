# SC1015 Mini-Project - Restaurant Conundrum

![Presentation Slide 1](https://user-images.githubusercontent.com/77908956/164874614-23a0d199-6666-44f0-941f-a1f807ba5682.png)


## About our project...
---
Our team's objective is to investigate the main reasons why customers order again on online delivery platforms in a metropolitan city in India, Bangalore.

Taking on the perspective of a restaurant owner, what and how would you change your operations to ensure customers are satisfied and order again? 

## How to navigate through our project!
---
All walkthroughs will be on a single file. (Note: Separate run needed for different methods of NLP used. Details included in the file.)

We recommend nbviewer to view our notebook because Github does not support anchor tags:
- https://nbviewer.org/github/DanielxDante/SC1015_SC3_Project/blob/main/main.ipynb#start

Else, for the whole experience, start by cloning our repository. After doing so, the third cell of our project notebook would contain the Table of Contents. Anchor tags for each segment of our project are inserted for immediate navigation. To access, simply click on the segment you wish to browse (has to be done in the Jupyter Notebook environment). 

All our code should be executed sequentially, except for the portion on Natural Language Processing under section 5 of our project. As we have two different methods of doing NLP, if you have already executed section 5.1, which is our first method of NLP using NLTK and SkLearn's TFIDFVectorizer, skip section 5.2 and continue with section 6. If you wish to proceed with our second method of NLP using the Pattern library, restart your kernel and execute sequentially again, skipping section 5.1 and execute from section 5.2 onwards.

For our SweetViz and Geographical Map Visualisations, if you experience any trouble viewing it, you can view it from the files placed in our repository under the Visualisations folder.  

Additionally, do note that GridSearchCV and Cross Validation takes a while to compute (especially so for XGBoost), so don't panic and be patient when running the cells!

## Problem Definition
---
- What are the optimal factors for a restaurant to attract consumers via food delivery service?
- Which model would be the best to predict it?

## Classification Models Used
---
- Logistic Regression
- K-Nearest Neighbours Classifier
- Random Forest
- XGBoost Classifier

## Conclusion
---
The top 3 things that customers, majority being university students with ages between 22-25, look out for in food delivery services are (of decreasing impact):
- Ease and convenience of delivery service
- Delivery services that save time
- Restaurants that have more offers and discounts

Turns out that people value their time and money! :astonished:

The model that produces the best score would be the Random Forest Model. However, it is possible that the most optimal classification model would be the XGBoost classifier for reasons stated in our walkthrough.

## What did we learn from this project?
---
- Using gmaps API for Geographical Analysis
- Vizualisations using SweetViz
- Natural Language Processing Techniques using NLTK, SkLearn's TFIDFVectorizer and Open Source Library Pattern
- Handling imbalanced datasets using resampling method SMOTE
- Logistic Regression, KNNeighbours, RandomForest Classification methods using sklearn
- XGBoost Classification API Usage
- Handling small datasets using Cross Validation Techniques
- Concepts about ROC-AUC, and F1 Score
- GitHub Collaboration

## Contributors
---
- @jonathannghj - Data Resampling, Data Preparation, Data Classification Modelling
- @DanielxDante - EDA, Natural Language Processing, Data Classification Modelling
- @ktnnm - EDA, Visualizations, Presentation

## References
---
- https://www.kaggle.com/benroshan/online-food-delivery-preferencesbangalore-region
- https://www.kaggle.com/code/rafjaa/resampling-strategies-for-imbalanced-datasets/notebook
- https://www.kaggle.com/code/qianchao/smote-with-imbalance-data
- https://www.kaggle.com/code/onadegibert/sentiment-analysis-with-tfidf-and-random-forest/notebook
- https://intellipaat.com/community/14889/f1-score-vs-roc-auc#:~:text=In%20general%2C%20the%20ROC%20is,area%20under%20the%20ROC%20curve.
- https://stackabuse.com/calculating-spearmans-rank-correlation-coefficient-in-python-with-pandas/
- https://towardsdatascience.com/how-to-encode-categorical-data-d44dde313131
