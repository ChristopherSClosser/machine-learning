# Machine Learning
Practice using Jupyter Notebook and other analysis packages to analyze data.

## Boston Housing

Analysis of the Boston Housing data, compiling data on home values in suburbs in Boston from 1993, from [sklearn](http://scikit-learn.org/stable/modules/generated/sklearn.datasets.load_boston.html).

Consists of 506 samples with the following categories:

|Field | Description |
|-------|-------------|
|CRIM   |  per capita crime rate by town |
|ZN     |  proportion of residential land zoned for lots over 25,000 sq.ft. |
|INDUS  |  proportion of non-retail business acres per town |
|CHAS   |  Charles River dummy variable (= 1 if tract bounds river; 0 otherwise) |
|NOX    |  nitric oxides concentration (parts per 10 million) |
|RM     |  average number of rooms per dwelling |
|AGE    |  proportion of owner-occupied units built prior to 1940 |
|DIS    |  weighted distances to five Boston employment centres |
|RAD    |  index of accessibility to radial highways |
|TAX    |  full-value property-tax rate per $10,000 |
|PTRATIO|  pupil-teacher ratio by town |
|B      |  1000(Bk - 0.63)^2 where Bk is the proportion of blacks by town |
|LSTAT  |  % lower status of the population |
|MEDV   |  Median value of owner-occupied homes in $1000's |

## Seattle PD 911 calls

Analysis of Seattle PD 911 call data, the first source consists of nearly 1.5 million records from 2010 to 2017.

The second is 1000 records from July to September, comparing calls to response locations.

Data used: [SeaPDIR](https://data.seattle.gov/Public-Safety/Seattle-Police-Department-911-Incident-Response/3k2p-39jp)

For analysis, fields were isolated and then compared using [Matplotlib](http://matplotlib.org/) for visualization.
