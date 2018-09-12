# Image-Classification-System-using-Decision-Trees
It is a typical notion that we don't use Decision Trees for continuous data. In this project, I have used Decision Tree Classification technique for image classification. 

The dataset used in this project was obtained from Yale Faces Dataset. This is a labelled dataset, making supervised learning possible. Initially the data was cleaned, that included reshaping all the images uniformly into a standard size. 

In order to reduce the model complexity for such a huge dataset, Dimensionality Reduction Technique - Principal Component Analysis was used. This is a dimensionality reduction technique that aims to find a dimension that minimises the reconstruction error and maximises the variance. 

On this reduced data, Decision Tree Algorithm was applied. For finding the optimal hyperparameters such as Maximum Depth of the Decision Tree, Grid Search Cross Validation Techniques were adopted. 

A final model using the optimal combination of Hyperparameters was developed using cross validation techniques.
