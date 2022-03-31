# 03-SVM

![Pairplot](pairplot.jpg?raw=true "Pairplot")
![KDE Plot](kdeplot.jpg?raw=true "Kdeplot")

## Head of data 
|    |   sepal_length |   sepal_width |   petal_length |   petal_width | species   |
|---:|---------------:|--------------:|---------------:|--------------:|:----------|
|  0 |            5.1 |           3.5 |            1.4 |           0.2 | setosa    |
|  1 |            4.9 |           3   |            1.4 |           0.2 | setosa    |
|  2 |            4.7 |           3.2 |            1.3 |           0.2 | setosa    |
|  3 |            4.6 |           3.1 |            1.5 |           0.2 | setosa    |
|  4 |            5   |           3.6 |            1.4 |           0.2 | setosa    |


## Results
### Confusion matrix
|    |    |    | 
|---:|---:|---:|
| 13 |  0 |  0 |
|  0 | 19 |  1 |
|  0 |  0 | 12 |

### Classification report
|           |   setosa |   versicolor |   virginica |   accuracy |   macro avg |   weighted avg |
|:----------|---------:|-------------:|------------:|-----------:|------------:|---------------:|
| precision |        1 |     1        |    0.923077 |   0.977778 |    0.974359 |       0.979487 |
| recall    |        1 |     0.95     |    1        |   0.977778 |    0.983333 |       0.977778 |
| f1-score  |        1 |     0.974359 |    0.96     |   0.977778 |    0.97812  |       0.977937 |
| support   |       13 |    20        |   12        |   0.977778 |   45        |      45        |