# Iris-dataset-Code-#The Iris dataset consists of 150 samples of iris flowers, each measured with four features: sepal length, sepal width, petal length, and petal width. These measurements are used to classify the iris flowers into three species: Setosa, Versicolor, and Virginica.  Key Attributes:  Sepal Length (cm) Sepal Width (cm) Petal Length (cm) Petal Width (cm)#
import numpy as np
import pandas as pd
import seaborn as sns
import matplotlib.pyplot as plt

from sklearn.linear_model import LogisticRegression
from sklearn.neighbors import KNeighborsClassifier
from sklearn.model_selection import train_test_split
from sklearn.preprocessing import LabelEncoder
from sklearn.metrics import accuracy_score

#implies machine learning algorithms
