# Real-estate-price-prediction
Data Science Regression project: Predicting home prices in Banglore

This Data Science project is about how to build a real estate price prediction.We first build a model using sklearn and linear regression using banglore home price dataset from kaggle.com.so here during data modeling we have used data science concepts like Data load and cleaning, Outlier detection and removal, Feature engineering, Dimensionality reduction, Grid searchcv for hyperparameter tunning, Kfold cross validations etc.

# Technologies and tools used
1. Python
2. Numpy and Pandas for data cleaning
3. Matplotlib for data visualization
4. Sklearn for model building
5. Jupiter notebook

# More about the project
->  data cleaning: As the dataset taken from kaggle is a raw dataset so firstly we need to do data cleaning where we remove the null values from the dataset and drop some       columns which are not required or the repeated ones.

->  After the data cleaning now we do feature engineering and dimensionality reduction (to reduce the size/dimensionalty of the dataset).Categorising certain values like
    in this dataset its about the no of bhks ,price,location of diffrent places in begaluru so we catogrize if any locatios have less than 10 datapoints they are 
    categorised under 'other'(it is a general category).
    
->  Then the outliers are detected and removed.As outliers represent extreme variations in dataset.so we need to remove them else they can cause variation in prediction.
    By graphically plotting a scatter plot we come to know the outliers and accordingly we can remove.
    
->  After outlier detection we will build a machine learning model and use kfold cross validations. Converting text(categorical info) to numeric data for analysis.Using 
    cross validation we get different scores which are majority mor than 80%. 
    
->  Using 5 fold cross validation for linear regression we are getting scor more than 80% we can also use other regression technique like lasso regression,descision tree 
    regression for trying all this and finding the most effective method we use Grid search cv (An API provided by sklearn).By applying grid search cv we come to know that
    linear regression model has around 81.83% score which is highest among Lasso and Descision tree so we choose linear regression model.
    
 -> Then we can enter the location, sqft, bhk, bathrom and we can get the estimated price. Also some comparisons are done in this project like if it is 2bhk with 3 
    3 bathroom  price and the appartment with 4 bhk and 3 bathrom price.
   
# conclusion
Over allit was a very interesting project. I got to know new terms like K fold cross validation.It was a great lerning and experience.
    
# Dataset
Dtaset was taken from kaggle.com
https://www.kaggle.com/datasets/amitabhajoy/bengaluru-house-price-data
