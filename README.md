# NYCBusinessComplaintMediation
Can we predict the satisfaction of mediation parties to a NYC Business Complaint?
The City of New York tracks consumer complaints against businesses that were mediated by the Department of Consumer Affairs (DCA).  The dataset contains data for last and current calendar years about the business, the complaint, and the outcome.  It also includes a “satisfaction” field, indicated whether or not both parties were satisfied with the outcome.   It excludes complaints that may have ongoing legal investigations.
There are many use cases for this dataset.  For example, the DCA Consumer Services Division can use the data to track satisfaction with the mediation services provided.  It can also leverage the data to track restitution amounts, as well as businesses with a large number of complaints.
For this analysis, we used basic statistical analysis, data exploration and visualization to gain an understanding of the data, and then used multiple techniques to predict if a new complaint will be satisfied or not based on other attributes, as well as a regression analysis to predict restitution amounts.   The data includes about 2600 hundred records and this may cause us to lean towards a cross validation approach but will still try other methods for training.    

The overall objective is to create a model to help predict if a complaint with both parties being satisfied or not.  
Note:  This data is fairly new which is one of the reasons we selected so that we are not influenced by other models that may exist for older data sets. 
