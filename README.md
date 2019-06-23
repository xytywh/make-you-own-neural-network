### make-you-own-neural-network(Python神经网络编程)
***
#### 书上相关代码以及自己的一些改进和理解(注释)
#### 书上的实现是一种简化的实现，很多地方并不完全正确，只是为了使初学者对整个神经网络的前向传播和反向传播有一个直观的认识。
#### 错误或者有待改进的地方包括但不限于:
- #### 1.输出层的激活函数，这里是多分类，应该使用softmax，但代码中使用的是sigmoid。虽然对简单的mnist分类影响不大，但其实是不对的。
- #### 2.hidden_errors的计算是经过了简化的，为了简单的说明问题，而并不保证完全的正确。

