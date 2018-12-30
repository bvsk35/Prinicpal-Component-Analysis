# Prinicpal-Component-Analysis
Keywords: PCA, SVD, GHA 

### Gist
This repo contains code for doing prinicipal component analysis using singular value decomposition (SVD) and genralised hebbian learning (GHA). 
1 - In SVD we develop sample covariance matrix and do eigen decompositions to calculate the all the prinicpal components. 
2 - In GHA we use a special neural network which is used to compute the prinical components. Network has single layer feedforward network with linear activation function and zero bias. After the training the weights converge to unit normal eigen vectors i.e. prinicipal components. Code has been written such way that we can extract desired number of principal component. This can be done changing simply the size of the weights. Weight matrix is NxM size where N is total number of samples and M is dimension of the original data. Similar input is of NxM size where N is total number of samples and M is dimension of the data.
3 - In the code for GHA final result was compared with SVD.
4 - Results have been uploaded for MNIST dataset dimensional reduction to 2D and 3D using SVD and have been plotted. 
