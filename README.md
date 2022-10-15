# ArtificialNeauralNetwork_predict_AND_OR_XOR
Perceptron to learn patterns in AND, OR and XOR, and make predictions given new input combination
we initialize the perceptron with random bias and weights
our learning rate is 1
X1, X2 are inputs while y is the expected output
The output of the perceptron is the sum of all weighted inputs plus the bias (In this case we attached a weight to the bias), then this passed through our Heaviside step function as activation function
ie output = f(X1.w1 + X2.w2 + bias.w3)
We then calculate error (y_true - y_predict), then use this range of error to adjust the weights and the bias 
ie weight = error * input * learning_rate

During training,
we train our perceptron over 50 episods while providing X1, X2 and the expected output so that it can learn by adjusting the weights over those 50 episodes untill optimum weights and bias are reached
