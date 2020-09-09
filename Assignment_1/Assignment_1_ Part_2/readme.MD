#Assignment1_part2_semi-learning

Jacky Chow (Jie Zou) ID:014545284

##Semi-supervised learning
 supervised learning training data very few labeled examples & large number of unlabeled examples.
- unlabelled data may require use/inspiration unsupervised methods (clustering and density estimation) 


##Target
In this colab, I will illustrate how Semi-supervised learning works through a simple example based on the credit_card_data.

##Results
'''
### tensorboard.dev
'''
https://tensorboard.dev/experiment/KpfJowPcRgq2S5X0lzYtLA/
'''

# Tuning Hyperparameters:
'''
- 8dropout-batchnorm-sigmoid-adam-binary_crossentropy-20epochs
- 0.8dropout-batchnorm-softmax-RMSprop-binary_crossentropy-20epochs
- 0.7dropout-batchnorm-softmax-RMSprop-categorical_crossentropy-20epochs
- 0.7dropout-batchnorm-softmax-adam-categorical_crossentropy-20epochs
- 0.6dropout-batchnorm-softmax-RMSprop-binary_crossentropy-20epochs
- 0.7dropout-batchnorm-softmax-RMSprop-binary_crossentropy-20epochs
'''

![image](https://github.com/zjzsu2000/CMPE297_Sec49AdvanceDL/blob/master/Assignment_1/Assignment_1_%20Part_2/tensorboard.jpg)

