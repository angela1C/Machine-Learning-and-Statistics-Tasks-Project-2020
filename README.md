# MachineLearningTasks2020
This is the repository for the Tasks assessment for Machine Learning and Statistics at GMIT 2020.

## How to download this repository

Go to the URL for the repository at https://github.com/angela1C/MachineLearningTasks2020 and click the green `Code` button. Follow instructions to clone.

## How to run the code


- Python 3 was used to develop this project and is needed to run the code in the notebook. Python 3 can be downloaded from the official Python website at https://www.python.org/downloads/. It can also be downloaded using the Anaconda Python distribution at https://www.anaconda.com/distribution/.

- The Jupyter Notebook tips-project.ipynb itself can be viewed directly in this GitHub repository in a browser without Python 3 being installed. On occasion the Jupyter Notebook may not render correctly in which case the url https://github.com/angela1C/MachineLearningTasks2020 can be copied and pasted in to the Jupyter nbviewer at https://nbviewer.jupyter.org where you enter the location of a Jupyter Notebook and click Go to have it rendered there.
---
## Task 1
October 5th, 2020:
Write a Python function called sqrt2 that calculates and prints to the screen the square root of 2 to 100 decimal places. Your code should not depend on any module from the standard library or otherwise. You should research the task first and include references and a description of your algorithm.

---
## Task 2
November 2nd, 2020: The Chi-squared test for independence is a statistical hypothesis test like a t-test. It is used to analyse whether two categorical variables are independent. The Wikipedia article gives the table below as an example [4], stating the Chi-squared value based on it is approximately 24.6. Use scipy.stats to verify this value and calculate the associated p value. You should include a short note with references justifying your analysis in a markdown cell.




|  | A | B | C | D | Total|
| -- | -- | -- | -- | -- | -- |
|White Collar|90 | 60 | 104 | 95 | 349 |
|Blue Collar |30 |50 |51|20|151
|No Collar |30 |40|45|35|150
|Total|150 |150|200|150 |650|

---

## Task 3

The standard deviation of an array of numbers x is calculated using numpy as $np.sqrt(np.sum((x - np.mean(x))&lt;/strong&gt;2)/len(x))$ . However, Microsoft Excel has two different versions of the standard deviation calculation, STDDEV.P and STDDEV.S. The STDDEV.P function performs the above calculation but in the STDDEV.S calculation the division is by len(x)-1 rather than len(x). 

Research these Excel functions, writing a note in a Markdown cell about the difference between them. Then use numpy to perform a simulation demonstrating that the STDDEV.S calculation is a better estimate for the standard deviation of a population when performed on a sample. Note that part of this task is to figure out the terminology in the previous sentence

---
## Task 4

Use scikit-learn to apply k-means clustering to Fisher’s famous Iris data set. You will easily obtain a copy of the data set on- line. Explain in a Markdown cell how your code works and how accurate it might be, and then explain how your model could be used to make predictions of species of iris.

---
# Task 2 References
[4] Wikipedia contributors, “Chi-squared test — Wikipedia, the free encyclopedia,” 2020, [Online; accessed 1-November-2020]. [Online]. Available: https://en.wikipedia. org/w/index.php?title=Chi-squared test&oldid=983024096