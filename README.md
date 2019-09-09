# Pytorch
</br> This repository is dedicated to building pytorch foundations. The readme will be updated as I write more programs

__Pytorch basics__
</br>This file explores the basics of Pytorch </br></br>

__Regression__</br>
1) Explores the relationship between dependent and independent variables.</br>
2) Gives the strength of each independent variable on the output. </br>
3) Results in continuous outputs. 
</br></br>
**Linear regression** </br>
It is used to predict continuous values. When you want to predict the output of a new x based on the predicted relationship between previous x and y in the dataset. Values range between (-infinity, infinity)
</br></br>
**Logistic regression**
Logistic regression too gives a continuous value but in the range of (0, 1)- probabilities. The output or the dependent variable is - data is either 0 or 1.  When you set a threshold for the output of logistic regression such as "above .5 probability then classify it as a certain category", you can apply logic regression for classification problems. Logistic regression can also be used for multi class classification if models are trained for each class separately and then combined.
</br>
 You can apply thresholds to linear regression outputs to do classification. However, everytime the dataset changes you need to change the threshold. The model should be able to learn the threshold from the dataset itself.



