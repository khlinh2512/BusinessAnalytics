# Machine Learning Algorithms

![image](https://github.com/khlinh2512/BusinessAnalytics/assets/118649367/5896cf2d-f02f-454c-979a-d68509d453c2)

![image](https://github.com/khlinh2512/BusinessAnalytics/assets/118649367/48c1f0e4-b7e7-4ccb-87e7-fb9de7d7ffc3)

![image](https://github.com/khlinh2512/BusinessAnalytics/assets/118649367/9771a350-55d9-479d-9a9f-5e3485e9e7c4)

## 1. Supervised Learning
Supervised learning is a machine learning approach where algorithms learn from labeled data. The algorithm receives input data and corresponding correct output labels in this process. The objective is to train the algorithm to predict accurate labels for new, unseen data. 

![image](https://github.com/khlinh2512/BusinessAnalytics/assets/118649367/78843276-8ddf-48f0-a60d-2236233dfef1)

Supervised learning can be further divided into two types:

### a. Classification
Classification is used when the output variable is categorical i.e. with 2 or more classes. For example, yes or no, male or female, true or false, etc.

![image](https://github.com/khlinh2512/BusinessAnalytics/assets/118649367/4d2cc27b-4f83-4837-986b-dde16660e64a)

In order to predict whether a mail is spam or not, we need to first teach the machine what a spam mail is. This is done based on a lot of spam filters - reviewing the content of the mail, reviewing the mail header, and then searching if it contains any false information. Certain keywords and blacklist filters that blackmails are used from already blacklisted spammers.

All of these features are used to score the mail and give it a spam score. The lower the total spam score of the email, the more likely that it is not a scam.

Based on the content, label, and the spam score of the new incoming mail, the algorithm decides whether it should land in the inbox or spam folder.
 

### b. Regression
Regression is used when the output variable is a real or continuous value. In this case, there is a relationship between two or more variables i.e., a change in one variable is associated with a change in the other variable. For example, salary based on work experience or weight based on height, etc.

![image](https://github.com/khlinh2512/BusinessAnalytics/assets/118649367/cb09612b-a385-4aaa-8eeb-f8ad1a0c1e42)

Let’s consider two variables - humidity and temperature. Here, ‘temperature’ is the independent variable and ‘humidity' is the dependent variable. If the temperature increases, then the humidity decreases. 
These two variables are fed to the model and the machine learns the relationship between them. After the machine is trained, it can easily predict the humidity based on the given temperature

### The most commonly used supervised learning algorithms are:
* **Decision Trees**
* **Support Vector Machines (SVD)**
* **Random Forests**
* **Naive Bayes**

These algorithms can be used for classification, regression, and time series forecasting tasks. Supervised learning is widely used in various domains, including healthcare, finance, marketing, and image recognition, to make predictions and gain valuable insights from data.

## 2. Unsupervised Learning
In Unsupervised Learning, the machine uses unlabeled data and learns on itself without any supervision. The machine tries to find a pattern in the unlabeled data and gives a response.

![image](https://github.com/khlinh2512/BusinessAnalytics/assets/118649367/fe1e1623-4443-4bb9-906b-1397814c98f0)

Unsupervised learning can be further grouped into types:

### a. Clustering
Clustering is the method of dividing the objects into clusters that are similar between them and are dissimilar to the objects belonging to another cluster. For example, finding out which customers made similar product purchases.

![image](https://github.com/khlinh2512/BusinessAnalytics/assets/118649367/8b225b26-c490-4347-99f7-8128b48920d9)

Suppose a telecom company wants to reduce its customer churn rate by providing personalized call and data plans. The behavior of the customers is studied and the model segments the customers with similar traits. Several strategies are adopted to minimize churn rate and maximize profit through suitable promotions and campaigns.

On the right side of the image, you can see a graph where customers are grouped. Group A customers use more data and also have high call durations. Group B customers are heavy Internet users, while Group C customers have high call duration. So, Group B will be given more data benefit plants, while Group C will be given cheaper called call rate plans and group A will be given the benefit of both.
### b. Association
Association is a rule-based machine learning to discover the probability of the co-occurrence of items in a collection. For example, finding out which products were purchased together.

![image](https://github.com/khlinh2512/BusinessAnalytics/assets/118649367/f2ba6f1d-7e29-4d96-9f74-8bc018912a73)

Let’s say that a customer goes to a supermarket and buys bread, milk, fruits, and wheat. Another customer comes and buys bread, milk, rice, and butter. Now, when another customer comes, it is highly likely that if he buys bread, he will buy milk too. Hence, a relationship is established based on customer behavior and recommendations are made. 

### The most commonly used unsupervised learning algorithms are: 

* **K-means clustering**
* **Hierarchical clustering**
* **Apriori algorithm**
* **Dimensionality Reduction Methods: PCA and SVD**
