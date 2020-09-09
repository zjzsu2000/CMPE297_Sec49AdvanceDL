#Assignment1_part1_MIL


Jacky Chow (Jie Zou) ID:014545284


MIL(Multiple Instance Learning) is a weakly supervised learning method that uses a set of labeled bags containing many instances instead of receiving a set of labeled instances.


> The character of  MIL is that individual unlabeled but bags/groups labeled. 
There are many applications, such as the medical field that all negative-is negative. (If at least one positive, a bag is positive)


In the MIL framework, slides are "packages" and tiles are "instances". By using it, we can save marking work and utilize weakly marked data.
When we receive a pathological section of a patient, we want to predict whether the large section contains cancer cells, or whether the patient has malignant cells. Multi-instance learning is a good choice because the doctor does not need to divide a single cell or divide each cell. Cells are labeled with tiles. Only the entire slide requires labels.
Generally, multi-instance learning can deal with classification problems, regression problems, ranking problems, and clustering problems, but here we will mainly focus on classification problems.
