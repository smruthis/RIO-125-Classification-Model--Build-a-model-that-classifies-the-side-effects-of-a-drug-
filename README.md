**OBJECTIVE**:

To build a classification model that classifies the side effects of a particular drug by Age, Race and Gender. For this we collected a dataset that contains details of some drugs. Dataset contains the details of 7093 drugs, their side effects and the rating of people about their satisfaction, effectiveness, ease of use etc.

**INTRODUCTION**
The healthcare industry has always been a strong supporter of cutting-edge
technologies. AI and ML have found several applications in the healthcare industry,
just as they have in business and e-commerce.
In the realm of pharmaceuticals, drugs play a pivotal role in treating a wide range
of diseases. However, they often come with inherent side effects that pose significant
risks to human health and pose challenges for pharmaceutical companies. The ability
to predict and anticipate the side effects of drugs has remained a persistent challenge
in the field of drug research. By leveraging machine learning methodologies,
researchers can explore novel avenues to tackle this challenge, aiding in the
development of more accurate prediction models for drug side effects. These
predictive models have the potential to enhance the safety profile of drugs, optimize
treatment plans, and support decision-making processes in pharmaceutical
development.

The steps done were:

• Data Collection

• Exploratory Data Analysis

• Data Preprocessing

• Model Building

• Hyperparameter Tuning

**DATA COLLECTION**

The dataset was collected from Kaggle. The link to the dataset is:
https://www.kaggle.com/datasets/rohanharode07/webmd-drug-reviews-dataset .

**EXPLORATORY DATA ANALYSIS**

The exploratory data analysis helped in obtaining the following conclusions:
The dataset contains 362806 rows and 12 columns.

• There are both numerical as well as categorical columns.

• 'Reviews' column has 37 missing values.

• Age group between 45 to 54 is the highest.

• Female patients are more than male patients.

• Statistical summary of the numerical columns.

• Top 15 drugs that are used mostly are obtained using a bar plot.

• Drugs mostly used by each of the age ranges are found separately:

▪ 75 or over: Lisinopril Solution

▪ 65-74: Lisinopril Solution

▪ 55-64: Lisinopril Solution

▪ 45-54: Cymbalta

▪ 35-44: Cymbalta

▪ 25-34: Lexapro

▪ 19-24: Mirena intrauterine device

▪ 13-18: Lexapro

▪ 7-12: Vyvnase

▪ 3-6: Vyvnase

▪ 0-2: Cefdinir

• Drugs mostly used by male is Lisinopril Solution and Lisinopril.

• Drugs mostly used by female is Cymbalta.

• In terms of rating, most effective drug with 5-star rating is Lexapro and least
rated one is Cymbalta.

• In terms of rating, most satisfied drug with 5-star rating is Lexapro and least
rated one is Lisinopril Solution.

• Lexapro, Cymbalta and Lisinopril Solution are plotted as pie chart on the basis
of effectiveness and satisfaction.

• Lisinopril solution used by people having high blood pressure.



• Heatmap was plotted to find the correlation between each feature. The
columns effectiveness and Satisfaction are highly correlated.

**DATA PREPROCESSING**

Data Preprocessing is a process of converting raw datasets into a format that is
consumable, understandable, and usable for further analysis.

This dataset has undergone the following preprocessing steps:

1.Removing null values

2. Handling of Outliers

3. Feature Reduction

4. Encoding

**MODEL CREATION**

As part of model creation, we have first splitted our dataset mainly to two:

⦁ Training Set

⦁ Testing Set

The training set is again divided into training and testing data. We have splitted the
training dataset such that training data accounts for 80% of training set and testing
data accounts for 20% of training set.
The column ‘Effectiveness’ is taken as the target column. 
Here, the accuracy of the model is 0.5901 using Gradient Boosting algorithm.

**HYPERPARAMETER TUNING**

The hyperparameter tuning process was conducted to optimize the machine
learning model's performance for predicting a target variable in the given dataset.

**CODE**: https://github.com/smruthis/RIO-125-Classification-Model--Build-a-model-that-classifies-the-side-effects-of-a-drug-/blob/main/Project%20code.ipynb

**FULL PROJECT REPORT**: https://drive.google.com/file/d/1JLWm0--BHEKNmelqLED60Lu9CGBEInyS/view?usp=sharing








