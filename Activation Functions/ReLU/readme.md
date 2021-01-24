# ReLU
Rectified Linear Unit or ReLU is another non-linear Activation Function widely used for it's ability to not activate all the neurons at once by activating only those neurons whose linear transformation is above 0.<br><br>
<img src="https://www.researchgate.net/profile/Hossam-H-Sultan/publication/333411007/figure/fig7/AS:766785846525952@1559827400204/ReLU-activation-function.png"><br><br>

### Advantages
- Computationally efficient—allows the network to converge very quickly.
- Non-linear—although it looks like a linear function, ReLU has a derivative function and allows for backpropagation.
### Disadvantages
- The Dying ReLU problem—when inputs approach zero, or are negative, the gradient of the function becomes zero, the network cannot perform backpropagation and cannot learn.