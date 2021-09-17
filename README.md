# pumpItUp
https://github.com/thanujamaheepala/pumpItUp

## Pre-Processing and Feature Engineering
### 1. Removing duplicated information columns
Dataset containes duplicated columns with same informations. Find those (using plots) and remove those duplicated columns.

ex: source, souce_type, source_class all these columns have same information. Select column with more categories, check null values and drop other columns.

### 2. Removing unimportant data for classification
 
ex: wpt_name, num_private etc. 

### 3. Filling null values
Dataset was checked for null values. Several columns had null values and all of them were categorical columns. Therefore Null values were filled using 'Unknown' label.

### 3. Replace values with low value counts
Some columns had low frequency values.

ex: funder columns had values even less than 10 value counts.

Replace those low frequency values with 'Other' label.

### 4. Mutual information
Plot and find best features.

### 5. Encoding and Normalization
Create 4 dataframes (label encoded, one hot encoded, label encoded with l2 normalized, onehot encoded with l2 normalized) and check those using a cross validation.

### 6. Model selection and hyper parameter tuning
Tested 3 models with different parameters using cross validation. RandomForest with default parameters gave best results.

## Proof of Submission
![pumtitUp](https://user-images.githubusercontent.com/47135905/133829357-af590170-2289-4036-a955-5eed44471743.JPG)
