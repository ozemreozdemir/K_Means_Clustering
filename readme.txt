K-Means Clustering
============================
#3. Run KMeansNormTest.R with TestObservations and TestCenters. 
#a) What is the single most obvious difference between the distributions of the first and second dimensions?
### The sizes of the dimensions are different, i.e. the data is not in equal terms.
#b) Does clustering in Test 1 occur along one or two dimensions? Which dimensions? Why?
### In Test 1, clustering occurs in one dimension, the second dimension since it has a larger scale/impact than first dimension. 
#c) Does clustering in Test 2 occur along one or two dimensions? Which dimensions? Why?
### In Test 2, clustering occurs in one dimension, the second dimension. Normalizing the first dimension makes its scale even more smaller compare to the second dimension. 
#d) Does clustering in Test 3 occur along one or two dimensions? Which dimensions? Why?
### In Test 3, clustering occurs in two dimensions. Even though the second dimension has a larger scale, de-normalizing reduced its impact and cluster in two dimensions.
#e) Does clustering in Test 4 occur along one or two dimensions? Which dimensions? Why?
### In Test 4, clustering occurs in two dimensions. Normalizing both dimensions balanced the impact of each dimension, i.e. it put the data in equal terms.
#4. Why is normalization important in K-means clustering? 
### It carries both cluster at an equivalent scale so that the impact of each dimension can be comparable in K-means clustering.
#5.How do you encode categorical data in a K-means clustering? 
### We need to transfer categorical values into numerical values, i.e. apply Binarization to be able to perform K-means clustering. 
#One way to do that would be define impact values of each category (for instance the number of repetition of each category) .
#6. Why is clustering un-supervised learning as opposed to supervised learning? 
### Unlike supervised learning which requires an expert label (or a specific function to guess dependent y via independent x), un-supervise learning users do not know what the outcome is.
### In clustering, we do not tell the algorithm what outcome was observed or what outcome is desired.