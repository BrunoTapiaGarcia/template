
Classification Modeling

Unsupervised Analysis Project

Case Information

A marketing consulting firm in Thailand has asked you to read the following research on Usage and Engagement Patterns for Facebook Live Sellers in Thailand Download Usage and Engagement Patterns for Facebook Live Sellers in Thailand.

 

Objective

Analyze the impact of photo content. In short, your company has long operated under the general idea that photos  are the most engaging form of social media content and that they should advise their clients to post as many of these as they can. 

 

Analysis Tasks/Questions

Provide an introduction to your analysis. 

In terms of reactions (likes, loves, etc.), how do photos perform when compared to other forms of content? Are they leading in terms of total engagement? What about in engagement on specific reactions? 
Develop principal components (PCA) based on the available social media metrics in the dataset. You may choose to group or exclude metrics as you see fit. 
Develop a scree plot and determine how many principal components you would like to retain. Draw a vertical line in the scree plot to indicate your cutoff point. 
Present the factor loadings for the retained principal components (correlations with the original features).
Interpret each of your retained principal components. 
Rename each principal component based on your interpretation of what it represents.
Develop segmentation with k-means clustering, using your retained principal components. You may also include additional features in your segmentation (avoid reusing features that were loaded into the principal components).
Decide on an ideal number of clusters and explain your rationale. 
Present and interpret each segment using cluster centroids and give an example of a "normal" post for each segment. 
Rename each segment based on your interpretation of what it represents.
Analyze the status types of each segment and report any findings related to photos. 

Develop three logistic regression models (1 = photo, 0 = not photo), each based on the following x-features.
Model 1: Original x-features
Model 2: Retained principal components
Model 3: Retained clusters

Select your best model from above and present the following:
Your rationale for why this is the best model. 
Model results: train-test gap based on accuracy and AUC score based on the results of the .predict step)
Confusion matrix: Explain each error and its associated risks for the business. 
 

Dataset

facebook_live_data.xlsx
