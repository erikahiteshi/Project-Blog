
# Supervised Learning
## Project: Breast Cancer Wisconcin Data Blog

### Install

This project requires **Python 3.6** and the following Python libraries installed:

- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org)
- [matplotlib](http://matplotlib.org/)
- [scikit-learn](http://scikit-learn.org/stable/)

You will also need to have software installed to run and execute an [iPython Notebook](http://ipython.org/notebook.html)


**Features**
1) ID number
2) Diagnosis (M = malignant, B = benign)
(3–32)
Ten real-valued features are computed for each cell nucleus:
a) radius (mean of distances from center to points on the perimeter)

b) texture (standard deviation of gray-scale values)

c) perimeter

d) area

e) smoothness (local variation in radius lengths)

f) compactness (perimeter² / area - 1.0)

g) concavity (severity of concave portions of the contour)

h) concave points (number of concave portions of the contour)

i) symmetry

j) fractal dimension ("coastline approximation" - 1)

For attributes (a) - (j), the mean, standard error and "worst" or largest (mean of the three largest values) of these features were computed for each image, resulting in 30 features. For instance, field 3 is Mean Radius, field 13 is Radius SE, field 23 is Worst Radius.

**Target Variable**
- `diagnosis`: Diagnosis Class (Malignant (1), Benign (0))

By using a mix of Machine Learning Algorithms, we were able to predict whether a lump was benign or malignant.
We could also see that some of the features were so prominent in the dataset that we could reduce it down to 6 features and still have results with accuracy of over 90%.
This implies that given a larger dataset, we could get timely predictions.

References:

Kagglecom. C. (2019). Kagglecom. https://www.kaggle.com/uciml/breast-cancer-wisconsin-data

Dua, D. and Graff, C. (2019). UCI Machine Learning Repository [http://archive.ics.uci.edu/ml]. Irvine, CA: University of California, School of Information and Computer Science

Pinkribbonfoundationorguk. C. (2019). Pinkribbonfoundationorguk. [Online]. [11 September 2019]. Available from: https://www.pinkribbonfoundation.org.uk/