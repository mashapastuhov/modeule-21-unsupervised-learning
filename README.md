# modeule-21-unsupervised-learning

The first model I ran, Charity, ended up with an accuracy score of 72.5%. I had 3 hidden layers with 80, 30 and 1 neurons.

After that I made an optimization - Charity Optimization 1. To this I added another layer, and more neuron - 4 layers total with 150, 90, 30 and 1 neurons. This ended up with an accuracy of 75.5% - it was unchanged.

My third attempt, Charity Optimization 2 , I kept the 4 layers, but adjusted the neurons to be 100, 40, 15 and 1, and more importantly I also "binned" the "Names" column. This resulted in an accuracy of 78.66%. This was adding extra features to the model, that are relevant information - well known Names have better branding and will affect the results. The same way people are more likely to trust google over bing or some other unknown brand.

The accuracy was still relatively low however. A random forest classifier would have worked better, and would have been a lot faster. This is because random forest is a robust and accurate model due to their sufficient number of estimators and tree depth. Also the random forest models have a faster performance than neural networks and could have avoided the data from being overfitted.
