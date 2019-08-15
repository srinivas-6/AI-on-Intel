# Data Wrangling with VMMRdb

Understanding ways to prepare the data set for machine learning and training. The dataset can be downloaded from [VMMR](http://vmmrdb.cecsresearch.org/). A subset of the relevant data used for training.

Here are the 10 most stolen used cars according to the NICB, with the most “popular” model year noted along with the total number of units from all model years taken:
- Honda Civic (1998): 45,062
- Honda Accord (1997): 43,764
- Ford F-150 (2006): 35,105
- Chevrolet Silverado (2004): 30.056
- Toyota Camry (2017): 17,276
- Nissan Altima (2016):  13,358
- Toyota Corolla (2016): 12,337
- Dodge/Ram Pickup (2001): 12,004
- GMC Sierra (2017): 10,865
- Chevrolet Impala (2008): 9,487

###  Select and Merge Interested Classes

Merging cars that are the same Make/Model but look at the years nearby since cars usually look the same for 3-4 years before changing styles. Below we will see the distribution of the data.

