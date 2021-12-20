# AI/ML Project - Customer Segmentaion 🧑🏻‍🤝‍🧑🏻👯🧑‍🤝‍🧑

<p align="center"><img src="https://user-images.githubusercontent.com/54996245/146764701-a341e41e-caaa-476a-9897-16c76f818203.jpg" style="width: 1000px;"/></p>

### Description:

A company that selling some of the product, and you want to know how well does the selling performance of the product.You have the data that can we analyze, but what kind of analysis that we can do?Well, we can segment customers based on their buying behavior on the market.
Keep in mind that the data is really huge, and we can not analyze it using our bare eye. We will use machine learning algorithms and the power of computing for it.

This project will show you how to cluster customers on segments based on their behavior using the K-Means algorithm in Python.
I hope that this article will help you on how to do customer segmentation step-by-step from preparing the data to cluster it.

### Acknowledgements:
This dataset has been referred from UCI ML Repository:
https://archive.ics.uci.edu/ml/datasets/online+retail

### Objective:
- Understand the Dataset & cleanup (if required).
- Build clustering model to segment the customer based similarity.
- Also fine-tune the hyperparameters & compare the evaluation metrics of vaious classification algorithms.

### Stractegic Plan of Action:
**We aim to solve the problem statement by creating a plan of action, Here are some of the necessary steps:**
1. Data Exploration
2. Exploratory Data Analysis (EDA)
3. Data Pre-processing
4. Data Manipulation
5. Predictive Modelling
6. Project Outcomes & Conclusion

### Some Visuals of the Project:

**1. RMF Variable Distribution**
  
<p align="left"><img src="https://user-images.githubusercontent.com/54996245/145871118-94783ddb-22cf-42a9-b36b-97bd44de95de.png" /></p>

**2. Transformed Vriable Distribution**

![image](https://user-images.githubusercontent.com/54996245/145871221-3a98693a-88ba-4d5a-aa44-af9e552a8f7e.png)

**3. Elbow Plot**

![image](https://user-images.githubusercontent.com/54996245/145871250-bfb94723-68ac-419e-af17-c63bcdf058f3.png)

**4. Snake Plot**

![image](https://user-images.githubusercontent.com/54996245/145871310-bcfcf183-47b5-45a6-916e-a72015a7f1c4.png)
  
### Here are some of the key outcomes of the project:
- The Dataset was large enough summing around 5.4 lakh samples & we used a 10k subsamples for creation of the model. 
- For the segmentation we used RMF Technique to create working table as it is most common segmentation technique.
- Visualising the distribution of data & their relationships, helped us to get some insights on the relationship between the feature-set.
- Appropriate Transformations were applied on the data to satisfy the key assumptions. Followed by Standardization.
- K Means algorithm was applied and appropriate cluster number was selected using Elbow Plot.
- The results were interepreted by calculating the cluster means & it was visualised with help of snake plot.

