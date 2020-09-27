# Assignment3_Finetuning with simclr v2

Jacky Chow (Jie Zou) ID:014545284

## a) Use tensorflow hub model of simclr v2 and finetune and do supervised classification using simclrv2. Also compare the results with non simclr v2 method (regular resnet finetuning without simclr v2) 

Use tensorflow hub model of simclr v2 and finetune and do supervised classification using simclrv2. Also compare the results with non simclr v2 method (regular resnet finetuning without simclr v2)

refs:

*  https://arxiv.org/pdf/2002.05709.pdf
*  https://medium.com/analytics-vidhya/understanding-simclr-a-simple-framework-for-contrastive-learning-of-visual-representations-d544a9003f3c
*  https://amitness.com/2020/03/illustrated-simclr/
*  https://amitness.com/2020/02/illustrated-self-supervised-learning/

## b) Optional : Advanced topic (extra credit - optional - not mandatory - only for people who have
some time to work on.) : semi supervised training with simclr -v2

implement simclr-v2 in tensorflow 2 from scratch (using utility functions) and show it performs well in small data set

(imagenet-5 categories)

refs:
*  https://github.com/sayakpaul/SimCLR-in-TensorFlow-2


## c) Optional : Knowledge distillation with kera (knowledge distillation practice - student-teacher training)

Write a colab to do knowledge distillation in keras (student/teacher model) 

refs:
*  https://github.com/sayakpaul/Knowledge-Distillation-in-Keras


## pics:
'''
### a) 
![image](https://github.com/zjzsu2000/CMPE297_Sec49AdvanceDL/blob/master/Assignment_3/iterations_10_sess.jpg)
![image](https://github.com/zjzsu2000/CMPE297_Sec49AdvanceDL/blob/master/Assignment_1/Assignment_1_%20Part_2/gbm1-1.png)
![image](https://github.com/zjzsu2000/CMPE297_Sec49AdvanceDL/blob/master/Assignment_1/Assignment_1_%20Part_2/gbm1-2.png)

### d)
![image](https://github.com/zjzsu2000/CMPE297_Sec49AdvanceDL/blob/master/Assignment_3/d)_teacher_model_summary.png)
![image](https://github.com/zjzsu2000/CMPE297_Sec49AdvanceDL/blob/master/Assignment_3/d)_teacher_model_train.png)
![image](https://github.com/zjzsu2000/CMPE297_Sec49AdvanceDL/blob/master/Assignment_3/d)_teacher_model_evaluate.png)
![image](https://github.com/zjzsu2000/CMPE297_Sec49AdvanceDL/blob/master/Assignment_3/d)_student_model_summary.png)



