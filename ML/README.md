## 𝐌𝐚𝐜𝐡𝐢𝐧𝐞 𝐋𝐞𝐚𝐫𝐧𝐢𝐧𝐠

> - Unit I  : Introduction to Machine Learning
> - Unit II : Feature Engineering

---

## 𝐔𝐧𝐢𝐭 𝐈: 𝐈𝐧𝐭𝐫𝐨𝐝𝐮𝐜𝐭𝐢𝐨𝐧 𝐭𝐨 𝐌𝐚𝐜𝐡𝐢𝐧𝐞 𝐋𝐞𝐚𝐫𝐧𝐢𝐧𝐠

<div align=center>
  <br>

![image](https://user-images.githubusercontent.com/68887544/193409416-22389508-dcb2-48a7-bd7b-3cdb8a32d435.png)

  <br>
</div>

- Introduction to Machine Learning
> - The branch of artificial intelligence that deals with the study of algorithms and programs that help machines learn something automatically to result in better performance for a set of task over time is called as Machine Learning.

- Comparison of Machine Learning with traditional programming
- ML vs AI vs Data Science
`^ Will do later! Not having enough time to do trivial things`

- Types of Learning:
> - There are 4 types:
>   - Supervised
>   - Semi Supervised
>   - Unsupervised and
>   - Reinforcement

- Supervised Learning:
> - Supervised Learning is kind of machine learning where the algorithm is trained using labelled data (i.e. the training dataset having both input and output) to build a mathematical model.
> - Supervised learning is usually used for classification or predicting a particular value. (regression)
> - Example: Classifying if the given picture is of a cat or a dog.
> - Common Algorithms:
>   - Logistic Regression
>   - Naïve Bayes
>   - k-NN
>   - Linear Regression

- Semi Supervised Learning:
> - Semi Supervised Learning is a kind of machine learning technique that makes use of both labelled as well as unlabeled training dataset when learning a model.
> - It falls between Supervised and Unsupervised Learning hence it is a special instance of weak supervision.

- Unsupervised Learning:
> - Unsupervised Learning is a kind of machine learning technique that learns pattern by creating clusters in the data from unlabeled training dataset (i.e. training dataset that only contains input data.)
> - For example, given a dataset with pictures of cat and dog without labels, Unsupervised learning algorithm will generate two unnamed clusters that contains cat and dog data.
> - Unsupervised Learning algorithms are used to find patterns in the data and build recommendation engine.

- Reinforcement Learning:
> - Reinforcement learning are kind of machine learning algorithm which improves upon themselves and learn from new situations using a trial-and-error method.
> - In Reinforcement learning, favorable outputs are encouraged i.e. "reinforced" whereas unfavorable outputs are discouraged.

- Models of Machine Learning:
> - Geometric Models
> - Probabilistic Models
> - Logical Models
> - Grouping and grading models
> - Parametric and non-parametric models

- Geometric Models:
> - Model based on Geometric principles comes under Geometric Models.
> - In Geometric models, features could be described as points in two or three dimensional space i.e (x, y) or (x, y, z) axis respectively.
> - If the data isn't geometric, it can be modelled in a geometric manner considering it geometric for example: temperature as a function of time.
> - Example: Linear regression, etc.
> - There are two types of geometric models:
>   - Linear models : Geometric concepts like planes, line etc.
>   - Distance based models : Geometric notion of distance to represent similarity.

- Probabilistic Models:
> - Models based on the idea of probability to predict new entities are known as Probabilistic Models.
> - Probabilistic models incorporate random variables and probability distributions into the model of an event or phenomenon.
> - A Probabilistic model gives a probability distribution as a solution.

- Logical Models:
> - Model that uses logical expression to divide the instance space into segments is called as logical models.
> - Logical expressions are expressions that returns boolean true and false after evaluation.
> - Once the data is grouped using a logical expression, the data is divided into homogeneous groupings for the problem we are trying to solve.
> - There are two types of logical models:
>   - Rule models : Use a collection of `if-then` statements
>   - Tree models : `If` part of the rules are organized in a tree structure.
>   - ^ Both uses same approach to Supervised Learning

- Grouping Models:
> - Model that breaks the instance space into groups or segments is called as the grouping model.
> - The number of groups is determined at the training time.

- Grading Models:
> - Model that form one global model over the instance space is known as grading model.

`^ This needs to be done properly tomorrow. : Grouping and Grading Model`

- Parametric Models:
> - Models that requires a fixed number of parameters to build the model is called as parametric models.

- Non-parametric Models:
> - Models that does not require any specific parameter setting is known as non-parametric model.




## 𝐔𝐧𝐢𝐭 𝐈𝐈: 𝐅𝐞𝐚𝐭𝐮𝐫𝐞 𝐄𝐧𝐠𝐢𝐧𝐞𝐞𝐫𝐢𝐧𝐠

<div align=center>
  <br>

![image](https://user-images.githubusercontent.com/68887544/193409433-6b78728f-90f4-4a79-a1ea-e43967509c9e.png)

  <br>
</div>


- Concept of Feature:
> - A feature is a numeric representation of raw data.

- Feature Engineering:
> - The process of formulating the most appropriate features given the data, the model and the task.
> - It usually includes:
>   - Feature Extraction : Creating new features from existing features
>   - Feature Transformation : Replace missing features
>   - Feature selection : filter irrelevant or redundant features from the dataset
>   - Feature Creation : Identifies relevant features

- Preprocessing of Data:
> - The process of preparing raw data for building machine learning model is called as Preprocessing of data.
> - Real world data may contain noise, missing values and may be in an unusable format. Hence, it is necessary for the data to be preprocessed so that we could improve the accuracy and efficiency of the machine learning model.
> - Following steps are involved in it:
>   - 1. Get the dataset
>   - 2. Importing libraries
>   - 3. Importing the dataset
>   - 4. Handling the missing values
>   - 5. Encoding the categorical data
>   - 6. splitting the dataset into training and test set
>   - 7. Feature Scaling

- Normalization and Scaling:
> - In scaling, we transform the range of the distribution of the data.
> - In normalization, we transform the shape of the distribution of the data.
> - Scaling is done to fit the data into a defined scale.
> - Normalization is done to change our observations so that they can be described as  a normal distribution.

- Types of Scaling:
> - Simple-feature Scaling:
>   - Divide each raw value data by maximum value for the feature.
>   - Results in values between 0 to 1.
>   - Usually done on image data, where each value is divided by 255 (maximum image pixel intensity)
>
> - Min-max scaling:
>   - Takes each value and subtract the minimum, then divide it by the range(max-min).
>   - Resultant value ranges between 0 to 1.
>   

- Types of normalization:
> - Z-score or standard score:
>   - values are normalized using standard deviation and mean of the entire data.
>
> - Box-cox transformation:
>   - Normalization of non-normal dependent variable into normal shape.

- Standardization:
> - Standardization is done when the feature are measured in different measurement units.
> - Z-score is one of the most popular method to standardize the data.
> - Once the Standardization is done, all the features will have a mean of zero, and a standard deviation of 1 and thus, the same scale.

- Managing the missing values:
> - Delete the row
> - Fill in the missing value manually
> - Use a global constant to fill in the missing value.
> - Use a measure of central tendency for attributes to fill in the missing value
> - Use the most probable value to fill in the missing value.

- Introduction to Dimensionality Reduction:
> - Dimensionality: No. of input variables or features in a dataset is called as dimensionality.
> - Dimensionality reduction is a technique that reduces the number of input variables in a dataset.
> - Two main components:
>   - Feature selection
>   - Feature extraction
> - Dimension reduction techniques:
>   - Principal Component Analysis (PCA)
>   - Linear Discriminant Analysis (LDA)
>   - Generalized Discriminant Analysis
