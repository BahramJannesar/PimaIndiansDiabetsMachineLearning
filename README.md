# Machine Learning on Pima Diabets dataset
Diabetes is a chronic condition in which the body develops a resistance to insulin, a hormone which converts food into glucose. Diabetes affect many people worldwide and is normally divided into Type 1 and Type 2 diabetes. Both have different characteristics. This article intends to analyze and create a model on the PIMA Indian Diabetes dataset to predict if a particular observation is at a risk of developing diabetes, given the independent factors. This article contains the methods followed to create a suitable model, including EDA along with the model.
![](https://github.com/BahramJannesar/pima-indians-diabets-kmean/blob/master/image/1024px-Blue_circle_for_diabetes.svg.png)

## Who are Pima Indians

The Pima (/ˈpiːmə/) (or Akimel O'odham, also spelled Akimel Oʼotham, "River People", formerly known as Pima) are a group of Native Americans living in an area consisting of what is now central and southern Arizona. [Wikipedia](https://en.wikipedia.org/wiki/Pima_people) 

![](https://github.com/BahramJannesar/pima-indians-diabets-kmean/blob/master/image/Pima.jpg)

## Dataset
The dataset can be found on the Kaggle website. This dataset is originally from the National Institute of Diabetes and Digestive and Kidney Diseases and can be used to predict whether a patient has diabetes based on certain diagnostic factors.

### Dataset columns

* Pregnancies
* Glucose
* BloodPressure
* SkinThickness
* Insulin
* BMI
* DiabetesPedigreeFun
* Age
* Outcome

### Clustering with KMeans Algorithm :
according to the correlation digaram as you can see , the best parameters for drawing and show how is the algorithm worked , is , Age , BMI , Glucose . 

![](https://github.com/BahramJannesar/PimaIndiansDiabetsMachineLearning/blob/master/image/Correlation.png)

**before clustering :** 

![](https://github.com/BahramJannesar/PimaIndiansDiabetsMachineLearning/blob/master/image/Age%20Vs%20BMI%20%2C%20Before.png)

![](https://github.com/BahramJannesar/PimaIndiansDiabetsMachineLearning/blob/master/image/Age%20vs%20Glucose%20%2C%20Before.png)

**after clusterung :**

![](https://github.com/BahramJannesar/PimaIndiansDiabetsMachineLearning/blob/master/image/Age%20vs%20BMI%20%2C%20After.png)

![](https://github.com/BahramJannesar/PimaIndiansDiabetsMachineLearning/blob/master/image/Age%20vs%20Gluscose%20%2C%20After.png)

#### License
See full license on [this](https://opensource.org/licenses/MIT) ,Under MIT License 
