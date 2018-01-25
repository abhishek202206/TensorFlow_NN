# TensorFlow_NN
Implementation of 3 layer Neural Network Model using TensorFLow

# Problem Description
This is a Tutorial for understanding the implementation of Basic three layer of Neural Network Model for prediction the prices of a Video Game Prices. The Training Dataset has the following attributes:
  1.Critics Ratings
  2. is_action
  3. is_exclusive_to_us
  4. is_portable
  5. is_role_playing
  6. is_sequel
  7. is_sports
  8. suitable_for_kids
  9. Unit Price
  10. Total Earning

Variable X is defined which has all the attributes from the dataset except the Total Earning attribute. Variable Y stores the total earning attribute. A three layer Neural Network is defined using TensorFLow. The variables are then normalised using MinMax  Scalar function to a range between 0-1.

The first Neural Network layer has 50 Hidden Neurons (Attributes stored in Variable X). The initial weights for the Neurons are initialized to xavier initializer and the relu activation function is used.

The Second Neural Network layer has 100 Hidden Neurons. The initial weights for the Neurons are initialized to xavier initializer and the relu activation function is used.

The Third Neural Network layer has 50 Hidden Neurons. The initial weights for the Neurons are initialized to xavier initializer and the relu activation function is used.

The cost function is calculated using the squared error mean and the Adam Optimiser is used for minimizing the cost function. The model is tranined over 100 epochs and the model summary is written after  every 5 epochs.

The model is capable of predicting the prices for each of the video games in the test dataset based on the inputs present in the test dataset. The model achieved an approximate accuracy of around 96%.

 
