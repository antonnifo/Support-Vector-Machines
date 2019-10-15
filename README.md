## Support Vector Machines
**SVM's** are  supervised learning models with associated learning alogorithims that analyze data and recognize patterns. Used for classification and regression analysis. Given a set of training examples, each marked for belonging to one of the two categories, an **SVM** trainging alogorithim builds a model that assigns new examples into one category or the other making it a ***non-probabilistic binary linear classifier***  
### GridSearch  
Finding the right parameters (like what C or gamma values to use) is a tricky task! But luckily, we can be a little lazy and just try a bunch of combinations and see what works best! This idea of creating a 'grid' of parameters and just trying out all the possible combinations is called a ***Gridsearch,*** this method is common enough that ***Scikit-learn*** has this functionality built in with ***GridSearchCV!*** .The CV stands for ***cross-validation*** which is the GridSearchCV takes a dictionary that describes the parameters that should be tried and a model to train. The grid of parameters is defined as a dictionary, where the keys are the parameters and the values are the settings to be tested.  
### Projects  
* **Breast cancer wisconsin (diagnostic) dataset** [nb viewier](https://nbviewer.jupyter.org/github/antonnifo/scaling-umbrella/blob/master/Support%20Vector%20Machines%20with%20Python.ipynb)  
 The built in breast cancer dataset from Scikit Learn have been used here. It can also be found [here](https://goo.gl/U2Uwz2) . Features are computed from a digitized image of a fine needle aspirate (FNA) of a breast mass.  They describe characteristics of the cell nuclei present in the image.The actual linear program used to obtain the separating plane
in the 3-dimensional space is that described in:K. P. Bennett and O. L. Mangasarian: "Robust Linear
Programming Discrimination of Two Linearly Inseparable Sets", Optimization Methods and Software 1, 1992, 23-34. On the project  I have built a model and evaluted it using a confusion matrix and a classification report
