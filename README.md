# Income-Analysis-using-Machine-learning
The aim of this project is to be able to analyze the adult dataset and classify the annual income of an individual to either <50K or >50K category (binary classification). Various classfiers have been implemented and their performance have been compared to arrive at the best model for this particular dataset.

Using various machine learning algorithms in Scikit-Learn I will Analyze and Build models to predict a binary variable of whether a given individual in the data earns more, or less than $50,000 with respect to a number of features. 


I'll employ a number of different Machine Learning Algorithms to evaluate the Accuracy of the models.

## Python Packages:

* Scikit-learn
* Pandas
* Numpy
* Matplotlib
* Seaborn


## Classification Models Used:

* Logistic Regressions
* Decision Trees
* Random Forests
* Gaussian Naive Bayes

The Adult dataset
The information is a replica of the notes for the abalone dataset from the UCI repository.

1. Title of Database: adult

2. Sources:
(a) Original owners of database (name/phone/snail address/email address)
US Census Bureau.
(b) Donor of database (name/phone/snail address/email address)
Ronny Kohavi and Barry Becker,
Data Mining and Visualization
Silicon Graphics.
e-mail: ronnyk@sgi.com
(c) Date received (databases may change over time without name change!)
05/19/96

3. Past Usage:
(a) Complete reference of article where it was described/used
@inproceedings{kohavi-nbtree,
author={Ron Kohavi},
title={Scaling Up the Accuracy of Naive-Bayes Classifiers: a Decision-Tree Hybrid},
booktitle={Proceedings of the Second International Conference on Knowledge Discovery and Data Mining},
year = 1996,
pages={to appear}}
(b) Indication of what attribute(s) were being predicted
Salary greater or less than 50,000.
(b) Indication of study's results (i.e. Is it a good domain to use?)
Hard domain with a nice number of records.
The following results obtained using MLC++ with default settings
for the algorithms mentioned below.

4. Relevant Information Paragraph:
Extraction was done by Barry Becker from the 1994 Census database. A set of reasonably clean records was extracted using the following conditions: ((AAGE>16) && (AGI>100) && (AFNLWGT>1)&& (HRSWK>0))

5. Number of Instances
48842 instances, mix of continuous and discrete (train=32561, test=16281)
45222 if instances with unknown values are removed (train=30162, test=15060)
Split into train-test using MLC++ GenCVFiles (2/3, 1/3 random).
6. Number of Attributes
6 continuous, 8 nominal attributes.

6. Attribute Information:

    Age: The age of an individual.

    Workclass: The sector of the economy in which the individual is employed.

    Fnlwgt: A continuious measure which denotes the socio-economic condition of the individual.

    Education Number: Education level completed.

    Marital Status: Married-civ-spouse, Divorced, Never-married, Separated, Widowed, Married-spouse-absent, Married-AF-spouse.

    Relationship: Wife, Own-child, Husband, Not-in-family, Other-relative, Unmarried

    Race: White, Asian-Pac-Islander, Amer-Indian-Eskimo, Other, Black.

    Sex: Male, Female.

    Capital gains: Continuous value of cappital gain received that year.

    Capital Loss: Continuous value of cappital loss incurred that year.

    Hours Per Week: Number of hours subject worked per week.



7. Missing Attribute Values:
7% have missing values.

8. Class Distribution:
Probability for the label '>50K' : 23.93% / 24.78% (without unknowns)
Probability for the label '<=50K' : 76.07% / 75.22% (without unknowns)

9. Notes for Delve
One prototask (income) has been defined, using attributes 1-13 as inputs and income level as a binary target.
Missing values - These are confined to attributes 2 (workclass), 7 (occupation) and 14 (native-country). The prototask only uses cases with no missing values.
The income prototask comes with two priors, differing according to if attribute 4 (education) is considered to be nominal or ordinal.


Last Updated 8 October 1996
Comments and questions to: delve@cs.toronto.edu


