# Minor-project-verzeo
Clean data and perform EDA on data related to movies 
.
.
.
.
.
Machine Learning Project
Verzeo Major Project Batch:ML07B7

Team Members :
Arjun Tanpure 
Harshita Maurya
Kavvin UV
Nooreen Fatima
Vivek Kashyap
Vishnu madharapu
Tushar jain 
Shobhig Shome 
Mahima Reddem
Kini Sanjula 
Topic: Ensemble three classification algorithm and find which one is more accurate in predicting the result for the given dataset
Dataset: Tweet dataset
Library used: Pandas, Sklearn, NumPy, Matplotlib and Seaborn
Firstly , the dataset is imported to the jupyter notebook with help of pandas library. Initial stage is cleaning the dataset. We use inbuilt function call df.info() to find any missing values then we clean the dataset by removing all the unwanted values. The dataset is then divided into three - male, female, df as three datasets.
The “male” and “female” dataset are divided based on the gender. And the main dataset“df”contains both male and female gender and we ignore the other two gender categories such as “brand” and “unknown” because compared to other gender it is very low.
	We did some feature selection for the main dataset “df” and did some exploratory data analysis. Using seaborn libraries, we plot correlation of dataset and the dataset which does not show good correlation. so we expect the machine learning algorithm will be 55- 65% accurate.
	

Male and female dataset is used to find some interesting facts from the dataset like most common emotions/words used by Males and Females. With the help of library and python programming language we found the answer such as -
Most common words used by Males: {'get': 337, 'like': 300, 'im': 293, 'go': 231, 'one': 214, 'time': 201, 'dont': 195, 'love': 176, 'make': 175, 'new': 167, 'look': 164}
 
Most common words used by Females: {'im': 529, 'like': 386, 'get': 384, 'go': 329, 'day': 304, 'love': 303, 'one': 287, 'make': 242, 'dont': 238, 'time': 232, 'peopl': 202}
 

We chose three classification algorithms :
Naïve bayes
Decision tree
Random forest 
These are the algorithms we used. Before training we did feature selection. With the help of sklearn,seaborn library it is easy to fit, train and test each algorithm. 
Dependent variable is:  gender (taken along Y axis)
Independent variables are: trusted judgements, tweet count, retweet count, fav number, profile confidence, gender confidence (taken along X axis)
Split the dataset into X_train, X_test, Y_train, Y_test. Then train each algorithm and predict each algorithm accuracy. 


From the accuracy calculation , as we expected the algorithm accuracy lies somewhere around 55-65%. 
Accuracy of algorithm :
Naïve bayes: 62%
2. Decision Tree: 55%
3.Random forest: 58%
So, the best fitting algorithm for the dataset is Naïve bayes algorithm and Random forest.

