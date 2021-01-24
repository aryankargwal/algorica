# Leaky ReLU
Leaky Rectified Linear Unit or Leaky ReLU is a varient of ReLU devised to deal with the Dying ReLU problem by introducing a very small linear component for x < 0 avoiding the gradients to be 0.<br><Br>
<img src="https://cdn.analyticsvidhya.com/wp-content/uploads/2017/10/17161552/leaky-relu-300x300.png"><Br><Br>

### Advantages
- Prevents Dying ReLU problem.
### Disadvantages
- Leaky ReLU isn't able to provide consistent results for negative input values.