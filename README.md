# UCLA_CSX_450_Final
## 1. The domain of the problem
Data includes a few measurements of abalone, including sex, length, weight, rings, etc.Data comes from an original (non-machine-learning) study: Warwick J Nash, Tracy L Sellers, Simon R Talbot, Andrew J Cawthorn and Wes B Ford (1994) "The Population Biology of Abalone (_Haliotis_species) in Tasmania. I. Blacklip Abalone (_H. rubra_) from the North Coast and Islands of Bass Strait", Sea Fisheries Division, Technical Report No. 48 (ISSN 1034-3288. 
## 2. A problem statement in which you clearly define
The age of abalone is determined by cutting the shell through the cone, staining it, and counting the number of rings through a microscope. Instead of using this comlicated method, we're using some other physical measurements to predict the age of abalone. We'll use supervised learning to do a regression model to predict the abalone age.
## 3. Dataset Description
This abalone dataset has 4777 instances and 8 attributes, the size is 269 KB. The data types are factor, numeric and integer. There are 8 features (Sex,Length, Diameter, Height, Whole weight, Shucked weight, Viscera weight and Shell weight) and the rings are what we are looking for. 

![my image](https://github.com/lssnadia/UCLA_CSX_450_Final/blob/master/Screen%20Shot%202018-01-28%20at%208.17.13%20PM.png)

## 4. A proposed solution
We are going to create 3 different models and to use 3 different algorithm (LDA, KNN, and CART). We'll split the whole data set into 2 sets, one is for training, the other one for testing. Based on the result, we'll find out which model is the most accurate one.
## 5. A benchmark model
We're using a regression model, a good benchmark can be the mean of length/height or rings.
## 6. A performance Metric
we need to test our models, so we use 3133 instances to come up with the models and then we test the models against the other 1044 instances to see how accurate they are. We use ratio of the correct predictions of the model divided by total number of instances in the dataset.
