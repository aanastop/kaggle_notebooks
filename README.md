# Kaggle Notebooks


## house-price-prediction-from-listings-greece.ipynb

The aim of this kernel is to develop a DeepLearning model that predicts the price of a property. House listings are used as input data. Using listings may not be the most accurate source of truth, but it has certain benefits: A seller (or a buyer) wants to know the advertised price for a given property, even if he is willing to go higher/lower for the actual purchase. The other advantage is that this kind of data is publicly available and there is a great variety of houses for many different locations. Listings often change prices, so data needs to be updated regularly and make sure that the latest price is always presented. Listings that are removed are also depicted in the data - a removal though does not necessarily mean that the property has been sold, it may be that the listing has just expired.

The listings are for the 2 areas in Greece with the greatest density of population, which is Attika and Thessaloniki. Expanding the coverage in other areas is of doubtful value, given rural areas are more sparse and prone to outliers.

The categorical features are in Greek, so sorry about that! I'm including the translated values when possible and a description for each feature.

The dataset attached to this kernel has 20.000 entries and it is indicative. I'm including the R2 score for the full dataset and how the score improves when more data is used.
