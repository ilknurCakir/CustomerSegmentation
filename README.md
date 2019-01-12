# CustomerSegmentation

Creating Customer Segmentation for Bertelsmann / Arvato Project

Get to Know the Data:

azdias consists of 900k+ rows and 366 features. It is about some features 
about general population of Germany.

customers consists of 93000+ samples and 369 features. It includes the same 
features and three more about customers of mail-order organic-products-selling
company.

Preprocessing the Data:

First convert some specific values to np.NaN in each column. These specific
values are created manually in a seperate csv file named feat_info.csv. For 
instance, column 3 includes -1 and 9 to represent missing or unknown values. 
These values comes with the main data from Bertelsmann /Arvato. 

Drop all outlier columns in terms of the number of missing values. It is 
important to drop same columns from all seperate data. 

Drop all outlier rows in terms of the number of missing values it includes. 