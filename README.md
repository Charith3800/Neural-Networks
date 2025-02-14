NAME : CHARITH REDDY PUTTA,
Student ID : 700759727.
1.	Tensor Manipulations & Reshaping:
   This project demonstrates tensor manipulation and reshaping using TensorFlow. A random tensor of shape (4, 6) is created, and its rank and shape are determined using TensorFlow functions. The tensor is then 
   reshaped into (2, 3, 4) and transposed to (3, 2, 4). Additionally, a smaller tensor of shape (1, 4) is broadcasted to match the larger tensor's shape, and element-wise addition is performed. The project also 
   includes an explanation of TensorFlow's broadcasting mechanism, which automatically expands smaller tensors to match the shape of larger tensors for operations. The output includes the rank and shape of the 
   tensor before and after reshaping/transposing, showcasing the flexibility of tensor operations in TensorFlow. This exercise is a practical introduction to tensor manipulation, reshaping, and broadcasting in deep 
   learning workflows.
2.  Loss Functions & Hyperparameter Tuning:
   This project demonstrates the implementation and comparison of two common loss functions used in machine learning: Mean Squared Error (MSE) and Categorical Cross-Entropy (CCE). The true values (y_true) and model 
   predictions (y_pred) are defined, and the losses are computed using TensorFlow/Keras. Predictions are then slightly modified to observe how the loss values change. Finally, the results are visualized using a bar 
   chart created with Matplotlib, comparing the original and modified loss values for both MSE and CCE. This exercise highlights the differences in sensitivity and application of these loss functions—MSE for 
   regression tasks and CCE for classification tasks. The code is simple, modular, and can be extended for further experimentation with loss functions.
3.	Train a Model with Different Optimizers:
   This project trains a convolutional neural network (CNN) on the MNIST dataset to compare the performance of two optimizers: Adam and SGD. The model architecture includes convolutional, pooling, and dense layers, 
   and the dataset is preprocessed by normalizing pixel values and reshaping for compatibility. The model is trained for 10 epochs using both optimizers, and the training and validation accuracy trends are 
   recorded. Adam, with its adaptive learning rate, typically achieves faster convergence and higher accuracy compared to SGD, which uses a fixed learning rate. The results are visualized using accuracy plots, 
   showcasing the differences in performance between the two optimizers. This project demonstrates the impact of optimizer choice on model training and provides insights into their behavior in deep learning tasks. 
   The code is modular and can be extended for further experimentation.
4.	Train a Neural Network and Log to TensorBoard:
   This project trains a convolutional neural network (CNN) on the MNIST dataset and logs the training process using TensorBoard. The model architecture includes convolutional, pooling, and dense layers, and the 
   dataset is preprocessed by normalizing pixel values and reshaping for compatibility. The model is trained for 5 epochs with TensorBoard logging enabled, and the logs are stored in the logs/fit/ directory. 
   TensorBoard is used to visualize training and validation accuracy and loss trends, helping to analyze model performance and detect overfitting. By increasing the number of epochs, you can observe how the model's 
   behavior changes, particularly in terms of overfitting. This project demonstrates the importance of monitoring training metrics and provides a practical introduction to using TensorBoard for deep learning 
   experiments.
