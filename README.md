# MachineLearningTasks2020

This repository contains my submission for the Machine Learning and Statistics Tasks 2020 Project as part of the requirement for the for the Machine Learning and Statistics module at GMIT as part of the Higher Diploma in Computing and Data Analytics programme.

This repository contains the Jupyter notebook Tasks.ipynb which contains the main body of the work.
There are four separate tasks in the notebook which are laid out in order from Task 1 to Task 4. Each task is self-contained and can be viewed or run independent of the other tasks in the same notebook. The four tasks were assigned at various dates in October and November 2020.

## How to download this repository

Go to the URL for the repository at https://github.com/angela1C/MachineLearningTasks2020 and click the green `Code` button. Follow instructions to clone to your local machine.

## How to run the code


- Python 3 was used to develop this project and is needed to run the code in the notebook. Python 3 can be downloaded from the official Python website at https://www.python.org/downloads/. It can also be downloaded using the Anaconda Python distribution at https://www.anaconda.com/distribution/.

- The Jupyter Notebook `tasks.ipynb` itself can be viewed directly in this GitHub repository in a browser without Python 3 being installed. On occasion the Jupyter Notebook may not render correctly in which case the URL https://github.com/angela1C/MachineLearningTasks2020 can be copied and pasted in to the Jupyter nbviewer at https://nbviewer.jupyter.org where you enter the location of a Jupyter Notebook and click Go to have it rendered there as a static version of the notebook.

The following Python packages were used for this project:
- [Python3](https://www.python.org) available at https://www.python.org
- [Jupyter Notebook](https://jupyter.readthedocs.io/en/latest/index.html) at https://jupyter.readthedocs.io
- [Python Pandas Library](https://pandas.pydata.org). A fast, powerful, flexible and easy to use open source data analysis and manipulation tool at https://pandas.pydata.org
- [Scikit-learn](https://scikit-learn.org/stable/) for Machine Learning in Python at https://scikit-learn.org
- [SciPy](https://docs.scipy.org/doc/scipy/reference/stats.html). A Python-based ecosystem of open-source software for mathematics, science, and engineering at https://docs.scipy.org
- [NumPy](https://numpy.org). The fundamental package for scientific computing with Python at https://numpy.org
- [Matplotlib](https://matplotlib.org). A comprehensive library for creating static, animated, and interactive visualizations in Python at https://matplotlib.org

- [Yellowbrick: Machine Learning Visualisation](https://www.scikit-yb.org/en/latest/)

These packages can be installed if necessary on the command line using `pip install <package name>`. Most of them come with the Anaconda distribution of Python 3. I did have to install the YellowBrick package using `pip install yellowbrick`.

The notebook containing all the work is named `tasks.ipynb`. If the repository is downloaded it can be run locally by navigating to the folder and entering the command `jupyter lab` or `jupyter notebook` on the command line. This will open Jupyter in the browser. The `tasks` notebook can be opened then within the Jupyter session. Once opened you can can select `Restart and Run All` from the `Kernel` menu. You can also run the selected cells and advance through the notebook using the run icon. 
The code for each task should be run from top to bottom but each of the four tasks are self-contained in their own section and the code for one task will not have any impact on the code for the other 3 tasks. The Python libraries used for each task are imported at the start of each task.

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

November 16th, 2020:The standard deviation of an array of numbers x is calculated using numpy as `np.sqrt(np.sum((x - np.mean(x))&lt;/strong&gt;2)/len(x))` . However, Microsoft Excel has two different versions of the standard deviation calculation, STDDEV.P and STDDEV.S. The STDDEV.P function performs the above calculation but in the STDDEV.S calculation the division is by len(x)-1 rather than len(x). 

Research these Excel functions, writing a note in a Markdown cell about the difference between them. Then use numpy to perform a simulation demonstrating that the STDDEV.S calculation is a better estimate for the standard deviation of a population when performed on a sample. Note that part of this task is to figure out the terminology in the previous sentence

---
## Task 4

November 30th, 2020: Use scikit-learn to apply k-means clustering to Fisher’s famous Iris data set. You will easily obtain a copy of the data set on- line. Explain in a Markdown cell how your code works and how accurate it might be, and then explain how your model could be used to make predictions of species of iris.

Updated December 16th, 2020: `k-means` was accidently written instead of `knn` for k Nearest Neighbours. Either algorithm can be used for this task.

---
# References

The references used in the project are noted throughout the notebook in the section in which they occur and all references for the four tasks are listed at the end of the notebook. Any quotes or direct references are noted specifically in the task in which they occur. 
Resources that were used to gain an understanding of some of the topics involved but were not used directly in the notebook are also listed.

