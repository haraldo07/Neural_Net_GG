On comparing the WhiteBox and BlackBox NN for the current dataset, WhiteBox gives more accuracy than BlackBox(2.5% more) and trains faster as for 
loops works faster than model optimizer. There was only 200 data for my drug classification problem, so as a result whitebox suits better. The 
activation function used in this model is both RELU and Softmax instead of Sigmoid because it is a multiclass classification problem, whereas sigmoid 
is most used for two class classification problem. In BlackBox, the epoch value was raised till 2000 beyond which the accuracy decreases, whereas
WhiteBox took 8000 iterations with a learning rate of 5% 
