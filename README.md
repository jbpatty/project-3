# project-3
Metis Data Science Bootcamp Project 3

Project Title: Predicting Start-up Successes

Venture Capitalist’s source thousands of potential investments annually and use early performance data to predict future outcomes. 
VCs raise capital from limited partner and startups raise money from VCs. But how do investors at all layers of the capital stack cash out?

Liquidity events, which come in two primary flavors: an exit via a merger or acquisition, or to list company shares on the public markets as an IPO.
The other side of the coin are companies who’s business models for one reason or another do not succeed. Some examples of successes and failures:
  * Alibaba raised $1.1B in funding and had a $167B valuation at its IPO
  * A notable recent M&A deal was Unilever’s purchase of Dollar Shave Club for $1B
  * Notable failures include Theranos which had raised $700M before closing and just
    last week Quibi announced its looking to sell off its assets after raising over $1.75B in funding
  
This is to say there are inherent risks in investing

My goal with this model is to limit these inherent risks by providing VCs with quantifiable data that determines where and when to invest, 
considering key factors that will decrease the overall failure rate and maximize the ROI of its portfolio companies.

My data came from Crunchbase and included companies with at least one round of funding between the decade 2005-2015. I utilized multiple classification 
models and Tableau as well as Python, Numpy, Pandas, Scikit Learn, and SQL.

My model was build on the machine learning algorithm Logistic Regression and included the following features “Funding Amounts”, “Funding Timing”, “Industry” 
and “Location” with the final metric a ROC AUC.

After training and testing my model I was able to increase the models prediction performance from 41% to 72%.  A high AUC score shows the model’s ability to 
separate True Successes vs False Successes which increases the model’s precision in predicting successful startups which will help limit the risk for VCs and 
its limited partners. 

Types of Classification Models:
* Logistic Regression
* ROC w/AUC
* Precision Recall Curve
* LogOdds
* Decision Tree -  - followed by Feature Importance
* kNN
* Naive Bayes
* Gaussian 
* SVM
* XGBoost
* Bagging Decision Trees
* Random Forest - followed by Feature Importance


