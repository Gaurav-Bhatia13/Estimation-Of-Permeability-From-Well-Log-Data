# Estimation-Of-Permeability-From-Well-Log-Data
Permeability is the property of a porous material that determines how easily fluid flows through that material, in response to an applied fluid pressure gradient. Reservoir permeability is a fundamental rock property which relate to its ability to flow when subjected to applied pressure gradients. This property has a significant impact on petroleum fields operations and reservoir management. In un-cored intervals and well, the reservoir description and characterization methods utilizing well logs represent a significant technical as well as economic advantage because well logs can provide a continuous record over the entire well. Hence, determination of appropriate value of Permeability from these logs are important for efficient interpretation purposes. 

Various Machine Learning Algorithms are trained on Volve Field dataset for estimation of rock permeability 

Introduction to Volve Field:
•	Location: Volve field is located at 200 kilometers west of Stavanger at the southern end of the Norwegian sector.
The Production period for which the dataset is obtained: 
                                12 February 2008 - 17 September 2016
•	Production: At plateau, Volve produced some 56,000 barrels per day and delivered a total of 63 million barrels in the mentioned interval.


Data Pre-Processing 
•	Data from 9 well logs were interpreted through LAS files and the files were converted to excel for collective analysis.
•	The missing and null values were filled with the mean of the column.
•	As a result, data of 7 columns and 47731 rows were obtained.
•	The 7 columns include- DEPTH, BVW, PHIF, SW, VCARB, VSH, KLOGH

Machine Learning is the field of study that gives computers the capability to learn.
4 Supervised Machine learning models are used in this project for the estimation of permeability from geophysical interpretation data of well logs. The Models used are namely:
•	Multiple Linear Regression
•	Decision Tree
•	Random Forest
•	Artificial Neural Networks

Note: All the models are trained using basic hyperparameters.

CONCLUSION

•	Permeability estimation from conventional well logs in heterogeneous formation is a difficult and complex problem to solve by statistical methods 
•	The parametric methods like statistical regression require the assumption for the satisfaction of multi-normal behavior and linearity. Therefore, an artificial neural network (ANN) as a non-linear and non-parametric tool is becoming increasingly popular in well log analysis.
•	Polynomial Neural Network (PNN) and Genetic Algorithm (GA), a new neural network approach to determine reservoir permeability from well logs is getting popular. 
•	Over-training or under-training is another pitfall. Over training of the network may result in the network memorizing the training set and lose its ability to generalize previously unseen data, while under-training of the network with low level of architecture cannot master the basic rules of the input patterns.
