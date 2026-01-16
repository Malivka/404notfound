

---

---

## **Q1: Numerical vs Categorical Features**

**Question (a):** From the dataset of a hospital (age, blood pressure, disease type, treatment success: Yes/No), mark which features are numerical and which are categorical.
**Answer:**

* Numerical features: age, blood pressure
* Categorical features: disease type, treatment success (Yes/No)

**Question (b):** Why might using a categorical column (like disease type) as a number cause wrong conclusions?
**Answer:** Using categorical data as numbers can lead to wrong conclusions because numbers imply order and distance, which categories do not have.

**Question (c):** Which ML algorithm would naturally handle categorical data well? Which one fits numerical better?
**Answer:**

* Categorical: Decision Trees, Random Forests
* Numerical: Linear Regression, SVM

---

## **Q2: Central Tendency and Spread**

**Question (a):** A company records the salaries of employees. If one CEO earns 1 crore while most others earn below 50,000, would you use mean or median to describe central tendency? Why?
**Answer:** Use **median** because it is not affected by extreme values like the CEO’s salary, unlike the mean.

**Question (b):** Define variance in your own words with an example.
**Answer:** Variance measures how far each data point is from the mean.

* Example: For [10, 20, 30], mean = 20 → variance shows spread of 10 and 30 from 20.

**Question (c):** How does standard deviation give more intuition about data spread compared to variance?
**Answer:** Standard deviation is the square root of variance, giving values in the same units as data, which makes spread easier to interpret.

---

## **Q3: Overfitting and Underfitting**

**Question (a):** A student memorizes last year’s question paper and scores well in mock tests but fails in the real exam. How is this similar to ML overfitting?
**Answer:** The student memorizing answers is like overfitting; the model memorizes training data instead of learning general patterns.

**Question (b):** List two strategies to improve generalization in models.
**Answer:**

1. Use regularization (L1/L2)
2. Use cross-validation or more diverse training data

**Question (c):** Explain with an analogy why underfitting is as harmful as overfitting.
**Answer:**

* Overfitting = memorizing without understanding
* Underfitting = barely studying
* Both cause poor real-world performance

---

## **Q4: Handling Missing Data & Outliers**

**Question (a):** A survey has missing “income” data for 10% of participants. Suggest two ways to address this issue.
**Answer:**

1. Imputation: Fill missing values with mean/median/predicted values
2. Deletion: Remove rows/columns with missing data

**Question (b):** In a dataset of house prices, one record shows a price 100× higher than others. What is this called? How can it affect predictions?
**Answer:** The record is an **outlier**; it can skew predictions and cause large errors.

**Question (c):** Which is worse for a model — systematic missing values or random missing values? Explain briefly.
**Answer:** Systematic missing values are worse because they follow a pattern and can bias the model.

---

## **Q5: Data Visualization Insights**

**Question (a):** A histogram of exam scores shows a long left tail. What does it suggest about student performance?
**Answer:** Long left tail indicates left-skewed distribution; most students scored high, few scored low.

**Question (b):** A boxplot shows several dots above the whisker — what does that mean?
**Answer:** Dots above whisker = outliers; students scoring much higher than others.

**Question (c):** Why might scatter plots help you guess relationships before fitting a model?
**Answer:** Scatter plots show patterns, trends, or correlations, helping guess relationships before modeling.

---

## **Q6: Features and Targets**

**Question (a):** In predicting house prices, which would be the features and which is the target?
**Answer:**

* Features: size, location, number of rooms, age
* Target: house price

**Question (b):** If one feature is strongly correlated with the target, how does it help the model?
**Answer:** A feature strongly correlated with target helps predict more accurately.

**Question (c):** Can we ever have multiple targets? Give an example.
**Answer:** Yes, multiple targets are possible (multi-output prediction). Example: Predict house price and rental value.

---

## **Q7: Types of Learning**

**Question (a):** Classify these scenarios: grouping songs by similarity, predicting next month’s rainfall, teaching a robot to balance.
**Answer:**

* Grouping songs by similarity → Unsupervised learning (clustering)
* Predicting rainfall → Supervised learning (regression)
* Teaching robot to balance → Reinforcement learning

**Question (b):** Why is supervised learning more common in industry?
**Answer:** Labeled data exists and performance can be measured.

**Question (c):** Give one benefit of unsupervised learning despite being harder to evaluate.
**Answer:** Discovers hidden patterns without labels; useful for insights or feature extraction.

---

## **Q8: Data Bias**

**Question (a):** A recruitment dataset contains more male than female applicants. What type of data bias is this?
**Answer:** Sampling/representation bias

**Question (b):** How can such bias affect ML model predictions?
**Answer:** Model may favor majority group, producing unfair predictions for underrepresented group.

**Question (c):** Suggest one way to reduce the impact of data bias.
**Answer:** Balance dataset: collect more female data or use resampling (oversampling/undersampling).

---

## **Q9: Model Complexity and Small Datasets**

**Question (a):** If you have only 50 data points, would you use a very complex model or a simple one? Why?
**Answer:** Use a simple model; complex model may overfit small dataset.

**Question (b):** What danger arises if the model has too many parameters compared to the dataset size?
**Answer:** Too many parameters may cause memorization instead of learning patterns (overfitting).

**Question (c):** Why do simpler models often generalize better on small datasets?
**Answer:** Simpler models focus on core patterns, not noise, and generalize better.

---


---
