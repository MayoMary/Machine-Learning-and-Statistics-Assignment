# Machine-Learning-and-Statistics-Assignment
This jupyter notebook analyses the Boston House Prices dataset utilising scipy, keras and Python packages. 

### Describing the dataset
Boston House Prices is based on housing data held by the United States Census Service pertaining to the area around Boston, Massachuttes. Each data sample relates to a particular town and has specific information based on various measurements. 
The dataset was first published in 1978 by Harrison, D. and Rubinfeld, D.L. in the folowing article - `Hedonic prices and the demand for clean air', J. Environ. Economics & Management, vol.5, 81-102, 1978.

The dataset is made up of 506 rows for the following 14 variables:
CRIM - per capita crime rate by town
ZN - proportion of residential land zoned for lots over 25,000 sq.ft.
INDUS - proportion of non-retail business acres per town.
CHAS - Charles River dummy variable (1 if tract bounds river; 0 otherwise)
NOX - nitric oxides concentration (parts per 10 million)
RM - average number of rooms per dwelling
AGE - proportion of owner-occupied units built prior to 1940
DIS - weighted distances to five Boston employment centres
RAD - index of accessibility to radial highways
TAX - full-value property-tax rate per $10,000
PTRATIO - pupil-teacher ratio by town
B - 1000(Bk - 0.63)^2 where Bk is the proportion of blacks by town
LSTAT - % lower status of the population
MEDV - Median value of owner-occupied homes in $1000's

### Data source
URL: http://lib.stat.cmu.edu/datasets/boston

### Code language
Jupyter Notebooks using Python.

### Libraries used
* Pandas - 0.25.1
* Matplotlib
* numpy
* random
* pandas
* seaborn
* sklearn

### Neural Networks: 

##### Background
Neural Networks were first developed by Bernard Widrow when he was based in Stanford University in the 1950s. [1]
Other sources place the development of Neural Networks with Warren McCullough and Walter Pitts, both researchers at the University of Chicago who moved to the Massachusetts Institute of Technology in 1952. [2]

Essentially Neural Networks are method for doing machine learning and are therefore a different model than the original von Neumann computer machines which were concerned with memory and processing of information processing.  Nueral Networks allow a computer to perform a task by analysing training examples. For example, an image recognition system will have been preloaded with lots of pictures of houses, cars, builsings etc in advance so that it can create patterns that will give identify images consistently. 

##### Process
In order for Neural networks to perform, they must be trained and this is where the various nodes are organised into layers. The data moves through the nodes in one direction only. However, one node may be connected to several other nodes which are a layer underneath it which sends data to it or above it where it sends data to. All of these are interconnections and are given a number described as a 'weight'.  Once the neural network is active and the node receives the second item of data which will be given a diferent number, it is then multiplied by the weight associated with it. Both are added together to then give one number. Thresholds are used and when the  number is below a certain value, then no data is passed to the next layer. And when the number is above a certain value, the node “fires,” as in sends the number which is the result of the weighted data input forward to its connections. 
As part of the training process, the weights and threshold get changes to ensure that they give the same results on a continuous basis.
When there are large databases, Neural networks are powerful in forecasting events.  

##### Current uses:
Current uses of Neural networks include the following: data mining, aerospace applications, industrial robotics, medical imaging, both voice and image recognition systems. 

REF: 
[1] https://www.webopedia.com/TERM/N/neural_network.html
[2] http://www.cs.stir.ac.uk/
[3] http://news.mit.edu/2017/explained-neural-networks-deep-learning-0414


### How to run Jupyter:
Install Jupyter notebook, navigate into its directory. Then open command prompt/terminal from there and run the command jupyter notebook and this will open up a page in the browser. Click on the desired file. 
Then from the Cell tab click Run All

Note: Please refer to the .ipynb file for a detailed report.
