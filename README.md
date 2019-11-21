# Neural-Networks

#### Generative Models for Text

- Attempt to build a generative model to mimic the writing style of British Mathematician,Philosopher, prolific writer, and political activist, Bertrand Russell.

- Implemented a LSTM by encoding characters into ASCII Code and rescaled for LSTM since it uses a sigmoid activation function


#### (Deep) CNN's for Image Colorization on CIFAR-10 dataset

- Implemeted k-means colorization by randomly selecting 10% of the 6000 X 32 X 32 pixes (each a RGB triplet)

  - Used k = 4 where the centers of the clusters were the final coloring of the pixels
  
- Deep CNN with 2+ multi-layer perceptron layers

  - Converted images to grayscale for CNN
  
  - Used 5 x 5 filters and a softmax output layer
