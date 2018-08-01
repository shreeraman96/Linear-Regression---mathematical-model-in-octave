# Linear-Regression---mathematical-model-in-octave
Linear regression implemented using octave scripts

### This is a programming assignment done for Online Machine learning course by Andrew NG

#### Files included :
	* ex1data1.txt - Text file that contains the data used
	* ex1.m - Main octave script that runs the linear regression for the data
	* plotdata.m - Octave script that contains the function to plot the data
	* computecost.m - Octave script that contains the function to calculate the cost function
	* gradientdescent.m - Octave script that contains the function to run gradient descent for any data

#### The Problem statement was obtained from Machine learning by Andrew NG course

#### Problem - Predicting the profit given the population

#### Problem type - Linear Regression with Single variable

#### Machine learning algorithm used : Linear Regression with Gradient Descent

#### Platform Used : Octave

Algorithm : 

	* Read the data from the file
	* Separate and process the feature and output vector
	* visualise the data using a scatter plot 
	* Initiliase parameter, learning rate and number of iterations
	* Define computecost.m to create a function to calculate the cost function
	* Define gradientdescent.m to create a function to run gradient descent for the data
	* Plot the linear fit for the data over the scatter plot 
	* Predict the profit for the desired population
	* Visualize cost function using surface plot and contour plot
	
#### Variables - codebook:
	* X - population vector
	* y - profit vector
	* theta - parameter vector
	* alpha - learning rate
	* iterations - Number of iterations
	* J - value of cost function
#### Functions defined :

##### computecost 
	* Input - X,y,theta
	* Output - J

##### gradientdesc
	* Input - X,y,theta,alpha,iterations
	* Output - theta,J_hist
