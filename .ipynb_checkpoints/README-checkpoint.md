# Dr. Evil Takes Ames, IA
#### Brandon Greenspan: [LinkedIn](https://https://www.linkedin.com/in/brandonlgreenspan)

## Problem Statement
Dr. Evil needs to build a new lair, and since Iowa State has the best Evil Communications school in the country, he chose Ames, IA for their workforce. ONE MILLION DOLLARS doesn’t doesn’t run a freaking evil empire like it used to, ok? We need to budget wisely, and that can’t all go to the house. When Dr. Evil commandeers a house, he pays what he thinks is fair, so he wants me, his Number 3, to determine what fair is, and doesn’t want me to be wrong. He’ll punish me if we pay more than 50,000 USD off from the actual value, making RMSE our metric because it is measured in the same unit as our predictive value. I don’t want to be wrong and be very badly hurt. All I had to make my predictions were data from the Ames Assessor’s Office on properties sold from 2006-2010. This was collected by Dr. Dean De Cock at Truman State University. Using a lasso regression, I take my evil features and do my best to minimize the predictive error.

## Executive Summary
Dr. Evil needs an evil lair and has decided to build it in Ames, IA in order to take advantage of the local workforce.  Iowa State is home to the most evil Communications program in the nation, which will make for good evil employees.

In order to best understand the housing market, the Evil Doctor, Doctor Evil, has assigned me, Number 3, to build a "model" that accurately predicts housing prices in Ames.  After loading in the data from Dr. De Cock (not an evil Doctor), I had a lot of evil cleaning to take care of.  Dr. Evil did not want me to eliminate any outliers because he did not want to eliminate any potential homes that might have had built-in "magma" chambers.  Even though, I informed him that it wasn't an option under the misc. category, he promptly reminded me of his evil credentials, and I obliged.  After filling in null values as zeros or "none" depending on the intended datatype, and changing ordinal categories to numerical values, EDA revealed the different features that already had a linear relationship with sale price.

We wouldn't be much of an established evil organization without good feature engineering practices.  While usually reserved for engineering evil animals like a lemhog (lemming * hog), we redesigned it to evil engineer features for our "model."  Rumor has it that Dr. Evil's father feature engineered the question mark.  A lot of our engineered features showed strong correlations to price, especially our "Evil Petting Zoo" feature which looked at high quality outdoor space which we interacted with Miami's zipcode (which is usually a predictor of success among evil bald men).  We started with a simple model of only 10 features, but when Dr. Evil learned that he doesn't pay extra for extra features, he wanted all of the freaking evil features in the "model," so we used all 242.

Using the RMSE as our evaluative metric, we discovered that the Lasso model performed best, and we are ready to unleash it on the world.

## Project Files
These data came from this:
[Training Set](datasets/train.csv)
[Test Set](datasets/test.csv)


## Data Dictionary
[Data Dictionary](http://jse.amstat.org/v19n3/decock/DataDocumentation.txt)


## Conclusion
Our model was actually underfit, making it a greater predictive model than inferential model, even as price increased.
Good evil lairs require optimal outdoor space (Evil Petting Zoo feature).  Homeowners know this and charge accordingly.  A lot of the best-indicative features are subjective (like quality), but once we get our mind control device up to speed, we'll have even greater accuracy.

I am confident that this model will keep me alive.


## Recommendations
This model can be used specifically for Dr. Evil to pay fair value with little hassle.  Additionally, if being an Evil Doctor somehow fails again, Dr. Evil can use this model to go into real estate, which would require little sacrifice on the evil side of things.


## References
- [Data Dictionary](http://jse.amstat.org/v19n3/decock/DataDocumentation.txt)

A lot of references to the Austin Powers movies.


```python

```
