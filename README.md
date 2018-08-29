# Tobacco-Retailer-Mapping

To Learn More: https://researchblog.duke.edu/2017/08/10/pinpointing-where-durhams-nicotine-addicts-get-their-fix/
Paper Drating. Waiting to be published by spring 2019 in Tobacco Control. 

Machine Learning
Our aggregated dataset contains many retailers.
But not all may actually sell tobacco products. The next step was predicting such characteristics of a store.
• From the Counter Tools dataset, each retailer is listed as being in one of nine categories.
• Tokenized store names by breaking them down into n-grams. Calculated a modified version of the term frequency–inverse document frequency (tf-idf) score for each n-gram within each category.
• Used Jenks Natural Breaks to cluster tokens with similar scores together, and to determine which tokens were the best predictors for a store being in each category.
• Modeled a decision tree through R, where are training set was 70% of our data and our test set the other 30%.
• Predicted categories of retailers and other factors, such as whether tobacco and alcohol are sold in the store.
