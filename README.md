# Heart Disease Prediction

## Python Libraries
Python libraries are a collection of functions and methods that allows us to perform many actions without writing the code.

**NumPy**: NumPy is a very popular python library for large multi-dimensional array and matrix processing, with the help of a large collection of high-level mathematical functions. It is very useful for fundamental scientific computations in Machine Learning.<br /><br />
**Pandas**: Pandas is a popular Python library for data analysis. Pandas is developed specifically for data extraction and preparation.<br /><br />
**Matplotlib**: Matpoltlib is a very popular Python library for data visualization. It provides various kinds of graphs and plots for data visualization, viz., histogram, error charts, bar chats, etc.<br /><br />
**Scikit-learn**: Scikit-learn is one of the most popular ML libraries for classical ML algorithms.<br /><br />
Scikit-learn supports most of the supervised and unsupervised learning algorithms. Scikit-learncan also be used for data-mining and data-analysis, which makes it a great tool who is starting out with ML.<br /><br />
**Seaborn**: Seaborn is a Python data visualization library based on matplotlib. It provides a high-level interface for drawing attractive and informative statistical graphics.<br /><br />
**train_test_split**: It splits the dataset into a training set and a test set.<br />

## Dataset
The Heart Disease dataset has been taken from Kaggle. This database contains 76 attributes, but all published experiments refer to using a subset of 14 of them. It has a total number of 303 rows and 14 columns among which 165 have a heart disease.<br />
Data Source: [Heart Disease Dataset](https://www.kaggle.com/ronitf/heart-disease-uci)<br /><br />
*age*: age in years<br />
*sex*: (1 = male; 0 = female)<br />
*cp*: chest pain type<br />
*trestbps*: resting blood pressure (in mm Hg on admission to the hospital)<br />
*chol*: serum cholestoral in mg/dl<br />
*fbs*: (fasting blood sugar > 120 mg/dl) (1 = true; 0 = false)<br />
*restecg*: resting electrocardiographic results<br />
*thalach*: maximum heart rate achieved<br />
*exang*: exercise induced angina (1 = yes; 0 = no)<br />
*oldpeak*: ST depression induced by exercise relative to rest<br />
*slope*: the slope of the peak exercise ST segment<br />
*ca*: number of major vessels (0-3) colored by flourosopy<br />
*thal*: thalassemia (1 = normal; 2 = fixed defect; 3 = reversable defect)<br />
*target*: (1= heart disease or 0= no heart disease)
</div>


The project involved analysis of the heart disease patient dataset with proper data processing. Then, 5 models were trained and tested with maximum scores as follows:

- K Neighbors Classifier: 87%
- Support Vector Classifier: 83%
- Decision Tree Classifier: 79%
- Random Forest Classifier: 84%
- LogisticRegression:84%



K Neighbors Classifier scored the best score of 87% with 8 neighbors.

