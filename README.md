# Car-insurance-Linear-regression
First I went to kaggle and downloaded a car insurance file .csv
Then I opened my Visual studio code and made a new folder 
then New file using Jupter 
First I important all i need ( Pandas for data analysis, Matplotlib to do some plots for visualization, seaborn same also for data visualization,
numpy for some arithmetic and matrixs operations, then from sklearn i imported what i will need in my Machine learning which is Linear regression , Lasso , Ridge 

Then I read the file 
then got info to see if there is null or no and the data type of each column
then a describition of the file gave me ( count, mean, std, min , 25%, 50%, 75%, max)
then some plotting to help me visualize the data 
then to do Machine learning i Had to make all the data numerical 
so I changed Seller type, Transmission and fuel type to numerical data 
Then I set my X as all the data but i dropped Car_name and selling price. Car_name because it was object and selling price because i will use it in the Y axis
then Y = selling price
Then I start to split my data 90 train and 10 test in the X axis and Y axis
Then Wrote a display function which will give me a graph after i run my model and also give me the prediction and also the mean square error
Then i made a LinearRegression model 
run it 
and then visualize it 
then repeat with Lasso and Ridge

