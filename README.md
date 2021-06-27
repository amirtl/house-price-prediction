# house-price-prediction
A prediction for a dataset of house price with full analyze of each data in column, preproccessing, simple linear regression, multiple linear regresion and random forrest
# explanation
- I put the train and test dataset.
- assume that you only know that the dataset is for house prices. the purpose is to analyze each column in train dataset and minimize the squart of the MSE for prediction of the test dataset.
# how analysis
- first I specified categorical and numerical column.
- then I plot the boxplot for important column.
- then I preproccessed the categorical column using OneHotEncoding.
- after that I founded correlation for each pair of column(for P-value < 0.01)
- then I plot the the chart with the line that simple linear regression produced for 3 important pair of columns to predict the train data.
- then I used multiple linear regression and used every column to predict SalePrice and the squart of MSE became 67000
- then I used random forrest with 14 mtry and method of ANOVA and the squart MSE became 28000.
# ouput
the output is a .csv file with 2 columns. Id and Predicted SalePrice.
