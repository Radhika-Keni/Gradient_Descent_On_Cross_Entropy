# Gradient_Descent_On_Cross_Entropy
Implement Gradient Descent on Cross Entropy Loss Function


## Objective of this notebook
- To implement Gradient Decsent on Cross Entropy Loss function from a neural network perspective
- Details of the **problem statement**  , **data set** ,  **summary of the code/solution**  , **sample output/Prediction** from the program and **final result** of the project are listed in the sections to follow.

## Problem Statement/Prologue
Gradient Descent is where the magic happens and this optimization algorithm is used in many ML/DL algorithms such as Linear Regression, Logistic Regression , SVM & Neural Networks.We seldom have to implement this algorithm oursleves because the libraries implement it under the hood.

Inspite of being a fundamental concept in ML , this has always been a daunting concept , especially for beginners. Theortically it involves Calculus and Vector Algebra but how does it all pan out in terms of code ? Implementing the Gradient Descent algorithm helps one understand this algorithm at a granular level.

## Data Description:
The dataset is manually created for the purpose of this exercise

## Domain:
Deep Learning :Proof of concept

## Summary of the Solution/Code:
We will be finding the best fit sigmoid curve on the given data set using Gradient Decsent i.e we will be implementing gradient decsent on the CE loss function.Below is the step wise breakdown of the code
- We will begin by manually creating a 2D data set & visualize the data set
- Note here that at this point , we already know what the sigmoid model would be because we engineered the data set
- We will then implement Gradient Descent & see whether we can arrive at the same sigmoid curve gradient Descent algorithm
- We start at random point and and iteratvely keep reducing the loss until we arrive at the best fir curve
- Cross vaidate whether the "best fit" curve we arrived at through gradient decsnt is indeed the best fit curve.
- We will realize all the operations in matrix format because we are implemting this from a neural network perspective
- Refer **python worksheet  Gradient_Descent_On_CrossEntropy.ipynb** for the solution

## Visualizing Input :

![image](https://user-images.githubusercontent.com/68383273/229302322-6d7eb6f8-4057-4ef5-917f-5aa998e5f28c.png)


The above image depicts the following
- We start at a random curve (marked in RED)
- The BLUE line indicates the best fit curve which is our target
- We need to arrive at this line through the Gradient Descent Algorithm


## Intermediate Output :

![image](https://user-images.githubusercontent.com/68383273/229301836-5a9152ae-8124-44cf-acf6-2cb870c38010.png)

- The Green line in the above diagram indicates the curve that was arrived at by the gradient descent algorithm after 1 iteration

## Final Output :
![image](https://user-images.githubusercontent.com/68383273/229302203-93f5a290-ef07-4533-b737-31e30d0329bf.png)


## Result :
![image](https://user-images.githubusercontent.com/68383273/229302241-18104db2-c0e0-4690-ae14-896c9ba77e4a.png)


## References
The following references were used while creating this notebook:
- Post Graduation AI/ML Study Material by GL/UAT


