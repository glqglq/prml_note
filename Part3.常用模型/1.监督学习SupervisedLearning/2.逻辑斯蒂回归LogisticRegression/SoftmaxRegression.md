# 1.适用

用于多分类问题。

逻辑回归的genneralization

# 2.模型

# 3.策略

- MLE

$$
ℓ(\theta) = \sum_{i=1}^mlogp(y^{(i)}|x^{(i)};\theta) \\ =\sum_{i=1}^mlog\prod_{j=1}^k(\frac{e^{\theta_l^Tx^{(i)}}}{\sum_{j=1}^ke^{\theta_j^Tx^{(i)}}})^{1{(y^i=l)}}
$$

# 4.算法

- 梯度上升法
- 牛顿法