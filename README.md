# Project-2-Garment-Worker-Productivity-AI07
Productivity Prediction of Garment Workers

# Summary

This project targeted to had below criteria:

To produce prediction data of garment worker productivity by using the features from 
Garment-Worker-Productivity dataset
[Garment Worker Productivity Dataset][1]  and stored in csv file

[1]:https://archive.ics.uci.edu/ml/datasets/Productivity+Prediction+of+Garment+Employees#

## Dataset
 Dataset by UCI 
 
 The Garment Industry is one of the key examples of the industrial globalization of this modern era. It is a highly labour-intensive industry with lots of manual processes. Satisfying the huge global demand for garment products is mostly dependent on the production and delivery performance of the employees in the garment manufacturing companies. So, it is highly desirable among the decision makers in the garments industry to track, analyse and predict the productivity performance of the working teams in their factories. This dataset can be used for regression purpose by predicting the productivity range (0-1) or for classification purpose by transforming the productivity range (0-1) into different classes.
 
 ## Methodology
 
 Load the dataset into [Google Colabotary][2]
 
 [2]:https://colab.research.google.com/?utm_source=scs-index
 
 ![image](https://user-images.githubusercontent.com/110074843/182076649-9cb77964-f436-4ad4-b624-1511ce0077ce.png)
 
 Split the data into 20% validation data and 80& training data and drop the features that are not needed
 
 ![image](https://user-images.githubusercontent.com/110074843/182076847-94fa279e-b1df-4653-9c11-ff0138c41f13.png)
 
 Next, buiild the model as follow
 
 ![image](https://user-images.githubusercontent.com/110074843/182076923-dab92e20-d4bb-43f9-8713-0bd244b34bd4.png)

## Result

Validation Loss

![image](https://user-images.githubusercontent.com/110074843/182077004-50eacd2c-88a0-4eaf-9d5f-7a0728316e94.png)

Validation MAE 

![image](https://user-images.githubusercontent.com/110074843/182077088-678c5c7a-6a45-48c5-82e5-d8cae12690cf.png)

Print out the prediction dataframe and stored in csv file

![image](https://user-images.githubusercontent.com/110074843/182077211-d5cf698e-52ad-4c37-bd0c-9dd1ba57de98.png)



