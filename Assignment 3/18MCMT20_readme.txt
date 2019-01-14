Imports Used:
import numpy as np
from sklearn import svm,metrics
from sklearn.preprocessing import StandardScaler
from sklearn import preprocessing
from sklearn.decomposition import PCA
from sklearn.model_selection import KFold,GridSearchCV
from sklearn.metrics import accuracy_score
import pandas as pd
import warnings

Environment Details :
OS: Ubuntu
Anaconda - Jupyter

Exceptional cases:
Non Margin SVs are always zero in all the cases. Tried with multiple values of C and Gamma using grid search
