# Implmentation of Autoencoder model on fingerprint dataset

1. i was applying some autoencoder models and i wanted to try it out on a real dataset and see how could the network build up images again after bottlenecking the features of the dataset.

2. Even after bottlenecking the features of the dataset i added a variation in the dataset before applying it to see how the network deals with noise after training, so at the end you will see a part where i implmented a noise function and passed that input to the autoencoder and it still got good results.

3. Finally training was done on google collab free tier with a number of epochs = 3, you can increase the number of epochs and see if results are better.

Note : some helper functions are in the utils.py file attached in the repo.
