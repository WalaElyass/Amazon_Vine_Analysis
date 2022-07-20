# Amazon_Vine_Analysis


##  Overview of the analysis:
The purpose of this analysis is to stydy the reviews written by members of the paid Amazon Vine program and determine if there is any bias toward favorable reviews from Vine members in the dataset available For my case I choose to conduct this study on the US wireless by using AWS, postgresql, and PySpark in Google Colab.


## Results:
How many Vine reviews and non-Vine reviews were there? The global number of reviews is about 65 547, but a small number of then is paid, around 0.953 for 613 reviews. The large majority is unpaid for 64 934 reviews.

##Summary:
Based on our finding we can say that the 5 stars reviews are not the majority in the paid review. So, the tendency is that the review tend to be critical. To support this statement, we could take the “review_body” and analyze the Term Frequency-Inverse Document Frequency Weight and build and pipeline into to run the Model and determine the tendency of the reviews.
