# Text-Classification-Clustering

Link to Jupyter Notebook:

https://github.com/philipMLdatascientist/Text-Classification-Clustering/blob/main/HDS807%20HW4.ipynb

# Data Preparation

- I now have a general impression of the data and developed strategies for feature engineering.
- I have reviewed all of the feature names and I concur with their data types
- I have 4999 samples and 6 features.
- Of the 6 features, 1 is numeric and the remaining 5 are categorical.
- There are 33 missing values in the transcription feature and 1068 missing values in the keyword section. I will recheck these missing values after I subset the data to Cardiovascular/Pulmonary, Neurology, and Orthopedic and remove the missing entries.
- There are no duplicate entries
- The unnamed:0, sample name, description, and keywords features are redundant features and will be removed.

# Interpreting the Results
- Both of the classifiers yielded similar accuracy; however, The complement NB results were superior at nearly 90% vs. the multinomial NB at 87.3%.
- Reviewing the confusion matrices, it is evident that the orthopedic and cardiovascular/pulmonary medical specialties demonstrated higher precision via complement NB, whereas neurology noted higher precision via multinomial NB.

# Unsupervised Clustering
- The TSNE projection demonstrates that the majority of the clustering has been centered around the cardiovascular/pulmonary medical specialty, followed by orthopedic, and then neurology.
