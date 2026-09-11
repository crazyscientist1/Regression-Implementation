This is an old project I worked on in 2024 which performs linear regression on a dataset using elementary backpropagation.

Equation of a line
$$\hat{y} = b_1x + b_0$$


$$L_{MSE} = \frac{1}{n}\sum_{i=1}^n (y_i - \hat{y})^2$$
$$\frac{\partial L_{MSE}}{\partial b_1} = -\frac{2}{n}\sum_{i=1}^n(y_i-\hat{y})x_i$$
$$\frac{\partial L_{MSE}}{\partial b_0} = -\frac{2}{n}\sum_{i=1}^n(y_i-\hat{y})$$
$$$$

