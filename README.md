# AMNEmpExitPredection
Keras based ANN which predicts employee exit/leaving for a company

Keras based ANN architecture:
1. One Input Layer
   The Input layer takes 11 dimensions.
2. Two Hindden Layer
   The first hidden layer takes 11 demension and the second hidder layer 6 dimension. Both hidden layer uses activation function - "relu"
3. An Output Layer
   The output layer uses "sigmoid" activiation function.

This predictor also demonstates the concept of "One Hot Encoding" also
   
 The ANN is compiled using "adam" optimizer and loss function as "binary_crossentropy"

Using above ANN model, accuracy around 85% was achieved, which is NOT BAD!!!
