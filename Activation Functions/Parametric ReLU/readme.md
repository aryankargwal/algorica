# Parametric ReLU
Another varient for the Rectified Linear Unit which tries to solve the same problem as the Leaky ReLU trying to defuse the Dying ReLU problem and achieves that by introducing a new parameter for all the values below 0. However, it differs from the Leaky ReLU as the parameter over here can be learned during training for optimum results.<br><br>
<img src="https://cdn.analyticsvidhya.com/wp-content/uploads/2017/10/prelu-300x262.png"><br><br>

### Advantages
- Allows the negative slope to be learned.
### Disadvantages
- May perform differently for different problems.