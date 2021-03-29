# Credit Risk
## Imbalanced Learning

This notebook helps create models that can identify the creditworthiness of borrowers. A logistic regression model will be used to compare an original dataset with a resampled dataset. For both datasets we will get the count of the target classes, train a logistic regression classifier, calculate the balanced accuracy score, generate a confusion matrix, and generate a classification report.

![](Imshrd/Classification_report_imbalanced.png)

---

## Technologies

This project uses a Jupyter Notebook in Jupyter Lab with the following libraries:

- Pandas: to help with the robust amount of features that will help analyze and organize the data.
- HvPlot: to create interactive data visualizations and charts that are visually pleasing to the audience.
- sklearn: for importing the balancedaccuracyscore and confusion matrix to evaluate the model, train_test_split to split the data for the model, and LogisticRegression to determine the type of model to use. 
- Path: to read the data from CSV files.
- imblearn: to import classification_report_imbalanced and calculate the metrics of the model. We will also import RandomOverSampler to create a better balance between the datasets. 

---

## Usage

To succesfully run this notebook, please be sure to import the required libraries and dependencies:

```
import numpy as np
import pandas as pd
from pathlib import Path
from sklearn.metrics import balanced_accuracy_score
from sklearn.metrics import confusion_matrix
from imblearn.metrics import classification_report_imbalanced

import warnings

from sklearn.model_selection import train_test_split
from sklearn.linear_model import LogisticRegression
```

---

## Contributors

Michael Husary was the main contributer along with fellow classmates and the educational staff. 

--- 

## License
*(Not sure if a license was required on this Challenge)*


MIT
