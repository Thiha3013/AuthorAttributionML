# AuthorAttrubutionML

Attributing author of a blog using sklearn 


Data is divided into 2 sections with one having limited amount of characters and articles as features and the other utilizing all of the data inside the blog as features

features are then further split into 3 sections:
  1. all of the words inside the dataset
  2. only the function words
  3. frequency of words inside the data set
  
Average accuracy from using all the data inside each blog as features for all 3 of the split feature sets yields 56%. However, it can be seen that only a certain blogs are getting predicted for any given test data sets. This maybe because of said blogs having the most characters hence features.
 
Average accuracy from using limiting amount of characters and articles as features for all 3 of the split feature sets yields 11%. This maybe because the features sets are not big enough to accurately predict the correct author.

Modification of the data sets, blogs, maybe needed to increase the accuracy.
