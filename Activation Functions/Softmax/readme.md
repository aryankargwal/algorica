# Softmax
Softmax can be described as a combination of multiple sigmoid functions. Sigmoid functions are widely used for binary classifications but here by utilizing this binary classification multiple times to tackle multiclass problems. Like the sigmoid function this function returns the probability of a a datapoint to belong to any of the individual classes. <br><br>
<img src="https://charlielehman.github.io/post/visualizing-tempscaling/softmax.gif"><br>
Visualizing Softmax is difficult for more than 2 classes as the plotting will need higher dimensions.

### Advantages
- Able to handle multiple classes only one class in other activation functions—normalizes the outputs for each class between 0 and 1, and divides by their sum, giving the probability of the input value being in a specific class.
- Useful for output neurons—typically Softmax is used only for the output layer, for neural networks that need to classify inputs into multiple categories.