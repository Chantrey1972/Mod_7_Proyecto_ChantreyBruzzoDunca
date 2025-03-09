# Mod_7_Proyecto_ChantreyBruzzoDuncan
Predicción de raza/etnia basada en características de ganadores anteriores

Este proyecto es un modelo de Machine Learning que predice la raza/etnicidad de los ganadores de los premios Oscar basándose en ciertas características 
de los ganadores anteriores, utiliza un conjunto de datos que incluye información histórica de los premios y aplica técnicas de clasificación avanzadas.


Las siguientes instrucciones te permitirán obtener una copia del proyecto en funcionamiento en tu máquina local para fines de desarrollo y pruebas.

### PREREQUISITOS

Necesitarás Python 3 y las siguientes bibliotecas de Python instaladas en tu máquina:

- IMPORTAMOS LAS LIBRERIAS NECESARIAS

import pandas as pd

import numpy as np

- GRAFICOS

import matplotlib.pyplot as plt

from matplotlib import style

import seaborn as sns

- PREPROCESADO Y MODELADO

from scipy.stats import pearsonr

from sklearn.model_selection import train_test_split

from sklearn.metrics import mean_squared_error

from sklearn.linear_model import LinearRegression

from sklearn.linear_model import Ridge

from sklearn.linear_model import Lasso

from sklearn.linear_model import ElasticNet

from sklearn.linear_model import RidgeCV

from sklearn.linear_model import LassoCV

from sklearn.linear_model import ElasticNetCV

from sklearn.linear_model import LogisticRegression

from sklearn import preprocessing

from sklearn.preprocessing import LabelEncoder

from sklearn import metrics

from sklearn.model_selection import train_test_split, GridSearchCV

from sklearn.ensemble import RandomForestClassifier

from sklearn.metrics import confusion_matrix, accuracy_score, f1_score, classification_report

from sklearn.impute import SimpleImputer

import warnings

warnings.filterwarnings('ignore')



### INSTALACIÓN

Para instalar y ejecutar el proyecto en tu máquina local, sigue estos pasos:

-  Clonar el repositorio
git clone [https://github.com/tu_usuario/proyecto-oscar.git](https://github.com/Chantrey1972/Mod_7_Proyecto_ChantreyBruzzoDuncam)

- Navegar al directorio del proyecto
cd proyecto-oscar

- Instalar las dependencias

   pip install pandas numpy scikit-learn matplotlib

- Ejecutar el script
python proyecto_7_final.py

- Mod_7_Proyecto_ChantreyBruzzoDuncam
Proyecto 7 bootcamp



