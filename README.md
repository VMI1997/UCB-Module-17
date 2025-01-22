# UCB-Module-17

In this exercise, we leveraged the CRISP DM process to design and evaluate multple models on a sample problem.  That problem was to create a model to predict a customers likelihood to purchase a long term deposit product.

OVERALL OBSERVATIONS:
While a number of the models tested and optimized would likely be appropriate, I would recommend the use of the logistic regression model with L1 regularization because it provided nearly the best results while providing excellent insights into the key drivers of the model - which would
be critically important to drive business decisions and actions.
It is also worth noting that some of the key drivers of the model (i.e. key features) were:  the months of March and April (likely due to tax return season) and market conditions (as seen in the features "euribor3m" and "cons.conf.idx") and finally the rates associated with the products.

FINAL RECOMMENDATION:
Based on this analysis and the findings of these models, I would suggest leveraging the logistic regression model with L1 regularization - AND I would suggest that future campaigns target the above criteria to optimize success rates.

LOGISTIC NOTES:
The data used with "bank-additional-full.csv" - it may need to be re-uploaded to this notebook in order for it to be executed (it doesnt seem to save that as part of the notebook)
Additional notes and insights can be found within the notebook (Pract_App_Linderman.ipynb) in this directory along with all coding and analysis performed
