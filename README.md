# Basic-Data-Science

About the files : 

Dataset Creation -

random_decision(feature,options,size) 


It populates the different vector fields of the entities by
* Using a random function to simulate the toss of a coin
* If the result is a head, a random function chooses the option to be filled in each field
* If the result is a tail, a pre-defined option is filled in.




The average expense is filled according to the City to which he/ she belongs to.


A panda Dataframe is created and is populated by the vectors which were earlier filled in.




Analysis through Visualisation -


* A categorical scatterplot (catplot) from Seaborn is used to visualize the number of families with (0-5)  number of dependents.
* Catplot used to see the disparities in the number of single and married entities.
* The average incomes of the entity and his/her family were calculated using the mean method from statistics library.
* A function Pie_plot was written using the methods of matplotlib.pyplot and was used to divide the population based on its education status.
* The break-even capability of an entity was analyzed by checking the sign of the quantity
Entity_Family_Income -12*Dependents]*Avg_Exp_perMonth_perEntity
* If it was less than 0, it was labeled as a loan requirement
* If it was exactly 0, it was labeled as a break even
* If it was greater than 0, it was labeled as an entity capable of making savings
* This was visualized in a percentage pie chart made using the function Pie_plot
* The economic status of each entity was categorized using the following index
Excellent range = 500000 and more
Good range = 50000 to 500000
Moderate range = 10000 to 50000
Average range = 5000 to 10000
Poor range = 5000 and less
* The result was displayed using a pie chart.
* The ability to afford a car loan was judged based on the above-mentioned categorization presuming that a family would have to of at least ‘moderate’ economic status to afford the car loan.
* The ability to afford a home loan was judged based on the same above mentioned categorization presuming that a family would have to of at least ‘good’ economic status to afford the car loan.


Predictive Model is made to determine the economic status of the entity using KNN. 
Several metrics have been found for this model.
There is an 80-20 split between the training and testing data. 



Citations :

https://scikit-learn.org/stable/
https://seaborn.pydata.org
https://matplotlib.org
