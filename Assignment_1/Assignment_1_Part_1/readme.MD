#Assignment1_part1_MIL


Jacky Chow (Jie Zou) ID:014545284


MIL(Multiple Instance Learning) is a weakly supervised learning method that uses a set of labeled bags containing many instances instead of receiving a set of labeled instances.


> The character of  MIL is that individual unlabeled but bags/groups labeled. 
There are many applications, such as the medical field that all negative-is negative. (If at least one positive, a bag is positive)


In the MIL framework, slides are "packages" and tiles are "instances". By using it, we can save marking work and utilize weakly marked data.
When we receive a pathological section of a patient, we want to predict whether the large section contains cancer cells, or whether the patient has malignant cells. Multi-instance learning is a good choice because the doctor does not need to divide a single cell or divide each cell. Cells are labeled with tiles. Only the entire slide requires labels.
Generally, multi-instance learning can deal with classification problems, regression problems, ranking problems, and clustering problems, but here we will mainly focus on classification problems.

Packaging different lenders into a loan package to form mutual guarantees is also a good way to reduce loan risks. So we can use multi-instance learning this tool to achieve the goal (pack different lenders into bags, and label the entire group of lenders with the individual labels ).

## Target
In this colab, I will illustrate how MIL works through a simple example based on the German credit data set.

TensorBoard live at: https://tensorboard.dev/experiment/NBtoBFeWSN2dMjdvAXF5ng/

![image](https://github.com/zjzsu2000/CMPE297_Sec49AdvanceDL/blob/master/Assignment_1/Assignment_1_Part_1/hist1.png)

![image](https://github.com/zjzsu2000/CMPE297_Sec49AdvanceDL/blob/master/Assignment_1/Assignment_1_Part_1/hist1_loss.png)

