This is an old project I worked on in 2024 which performs linear regression on a dataset using elementary backpropagation.

Equation of a line 
$$\hat{y} = b_1x + b_0$$

Mean square error loss 
$$L_{MSE} = \frac{1}{n}\sum_{i=1}^n (y_i - \hat{y})^2$$

Gradient of loss wrt $$b_1$$ 
$$\frac{\partial L_{MSE}}{\partial b_1} = -\frac{2}{n}\sum_{i=1}^n(y_i-\hat{y}_i)x_i$$

Gradient of loss wrt $$b_0$$ 
$$\frac{\partial L_{MSE}}{\partial b_0} = -\frac{2}{n}\sum_{i=1}^n(y_i-\hat{y}_i)$$

Gradient descent 
$$b_1^{t+1} = b_1^{t} - \alpha * \frac{\partial L_{MSE}}{\partial b_1}$$
$$b_0^{t+1} = b_0^{t} - \alpha * \frac{\partial L_{MSE}}{\partial b_1}$$

