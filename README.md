
<h1> Post-Operative Life Expectancy in the Lung Cancer Patients </h1>

<h2> </h2>
<h2> Introduction</h2>

Post-operative life expectancy tool is an android application to predict the chance of survival or the possibility of death within 1 year after the lung surgery among the lung cancer patients.

<h2>Motivation </h2>

To predict the chance of survival after lung cancer surgery.
To use in personal life.
Also can be used for organizational purposes.
Doctors can understand the condition of their patients easily. 
Scope of the Project
The scope of this project is limited to use of the KNN (K Nearest Neighbour) algorithm. A patient can find the probability by providing his/her medical conditional attributes. The overall accuracy of the tool can also be checked through cross validation.


<h2>Methodology  </h2>

KNN Algorithm : <br>
I have used the K- Nearest Neighbor algorithm to find out the expected value. Here K indicates the number of nearest neighbours to be observed.

Calculating Distance :<br>
The Euclidean method is used to calculate the distances among the dataset instances. 

Cross Validation :<br>
I have implemented 10-fold cross validation. For each iteration, random number instances are picked to avoid redundancy.

Calculating Expected Attribute :<br>
By observing the nearest neighbours, we will count the most occurrences of expected attributes among the neighbours and choose the item.

<h2> Technology</h2>
Java, Android<br>
IDE : Android Studio <br>

<h2> References</h2>
1. UCI Machine Learning Repository: https://archive.ics.uci.edu/ml/datasets/Thoracic+Surgery+Data <br>
2. https://www.news-medical.net/news/20210219/COVID-19-and-lung-cancer-have-a-common-pathway-say-researchers.aspx <br>
