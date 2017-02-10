# tf-dann-py35
Tensorflow-gpu (1.0.0.rc2, Window, py35) implementation of Domain Adversarial Neural Network. 

Modified from [pumpikano](https://github.com/pumpikano/tf-dann)'s github

#CHANGE LOGS
**Blobs-DANN.ipynb**

0. Kernel: Python2 -> Python3
1. / -> //
2. specified arguments of softmax_cross_entropy_with_logits(logits = , labels = )
    e.g.)
    tf.nn.softmax_cross_entropy_with_logits(p_logit, y) 
    -> tf.nn.softmax_cross_entropy_with_logits(logits = p_logit, labels = y)
3. .next() -> \.\_\_next()\_\_
4. print ~ -> print(~)

**flip_gradient.py**

1. tf.neg(~) -> tf.negative(~)
