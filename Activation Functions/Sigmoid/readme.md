# Sigmoid 
One of the most used Activation Functions, Sigmoid transforms the input values between the range 0 and 1 and can be identified by the characteristic "S" shape graph.<br><br>
<img src="https://hvidberrrg.github.io/deep_learning/activation_functions/assets/sigmoid_function.png"><br><br>

### Advantages
- Smooth gradient, preventing “jumps” in output values.
- Output values bound between 0 and 1, normalizing the output of each neuron.
### Disadvantages 
- Vanishing gradient—for very high or very low values of X, there is almost no change to the prediction, causing a vanishing gradient problem. 
- Not zero centered.
- Computationally Expensive.