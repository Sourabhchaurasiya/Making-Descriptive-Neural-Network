                    Neural Network from Scratch

key features:
Vectorized Neurons & Layers:
      leverage NumPy’s np.dot and array broadcasting
Dense Layer Class:
      Multiple layers can be stacked to form deep networks. Biases are added via NumPy broadcasting, and we include utility methods to manage layer inputs and parameters in a clean, object-oriented way.
Activation Functions:
      The implementation includes Sigmoid, ReLU, and Softmax functions with their derivatives.
Forward Pass & Loss:
      Computed the cross-entropy loss for classification entirely from first principles.All vector and matrix operations (matrix-matrix products, sums) are implemented explicitly, so one can trace exactly how predictions are obtained.
Backpropagation:
      A full backward pass, calculating gradients of the loss with respect to every weight and bias
Optimizers:
      Gradient-based optimization methods are implemented in detail. We include vanilla Gradient Descent, momentum, and several adaptive methods: AdaGrad, RMSProp, and Adam.
      
Generalization & Evaluation:
      o prevent overfitting and evaluate performance, the project includes regularization techniques. K-fold cross-validation splits the data into k folds, training on k–1 folds and validating on the remaining fold; results are averaged over all folds
