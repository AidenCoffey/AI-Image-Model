In our analysis, we've discovered that not all methods perform equally well across different datasets. This article compares seven different algorithms for organizing data to determine their accuracy in terms of F1-score, precision, AUC, and recall. Specifically, we investigate which of the following seven algorithms works best for a basic AI image recognition database:

Perceptron,
Linear Regression,
Linear SVM (Support Vector Machines),
Non-Linear SVM (Support Vector Machines),
Decision Tree,
Random Forest,
and K-Nearest Neighbors.
We utilize a singular dataset containing 1,797 data pieces with 10 different classifications ranging from 0 to 9. Each image is represented as an 8 by 8 matrix, creating 64 pixels for the model to analyze for each testing and training sample.

Hardware and Software Specifications
All analyses were conducted on an AMD Ryzen 5 5625U with Radeon Graphics. We utilized SciKit-Learn with Jupyter Notebooks in Python version 3.9.18 for model implementation and analysis. Additionally, Matplotlib libraries were employed for data visualization, including plots and graphs.
