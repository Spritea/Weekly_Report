# Weekly Report
<sub>**Number:5  
Adviser: Prof. Yang Wen  
Student: Cheng Wensheng  
Period: 2017.12.18-2017.12.23**</sub>
## Recap
This week I mainly put my effort on the project. Senior Wei Guo shows me a project which works really well on Kaggle competition. I tried this. 
## Model
* This project uses 3 fancy models, including ResNet50, Inception v3, Xception. The author adds the 3 features of the 3 models together to form a new feature.
* The author submits [the model](https://github.com/ypwhs/dogs_vs_cats) to Kaggle. Result shows that the model ranks 20/1314. It's an excellent model.
## Experiment
* Firsly, I tried this on Airplane dataset. However, owning to the wrong annotations, the training set is not so good. As a result of that, the classification is only about 60%. So we need to switch to another set.
* Then I use another dataset of birds. The accuracy on validation set has reached 95%. Since we already have the whole dataset, if I use all the dataset, the accuracy on the whole dataset can reach 99%. Even I split the dataset to training set, validation set and test dataset, the accuracy on test dataset is still above 90%.