# WorthAutoCar

Machine Learning model for Predictive Pricing for Cars

Objective : To develop a Machine Learning model which accurately predicts the price of a car based on several features like Company, Model type, Manufacturing year, Engine size, Fuel type etc using algorithms like Linear Regression and KNN.

Exploratory Data Analysis: During EDA, we adopt a visual approach to analyze a dataset using statistical and graphical techniques, which ultimately enables us to identify patters and relationships in a dataset. The dataset provided to us consisted of several features pertaining to different attributes of a car like the Company, model, fuel type etc. Several insights were drawn from the data which are discussed in the upcoming slides.

Data Preprocessing: • We first tried to find missing values using the isnull().sum() function but fortunately the dataset didn’t have any missing values. • However the data points like company name, model and fuel type consisted of values with the ‘Object’ data type, they were encoded to ‘int’ type using replace function and label encoder

Model Building • Choice of Algorithm : Linear Regression • Reason : Linear regression is a common method for predicting car prices because it can predict values based on the correlation between variables. It is also quite simple to interpret and is very versatile in its nature of application.

Insights regarding the factors

• The dataset provided to us consisted of only 3 main features to carry out the price prediction, which are the company, model and fuel type. • These features comparatively provide lesser number of data points for the model to be trained successfully with a high accuracy.

Insights regarding the solution • However if we consider a different dataset which consisted of some additional features like kilometers driven, transmission type and seller type, we are able to train our model with a much higher accuracy due to the availability of more diverse data points. • The sample dataset is as follows- image

Evaluation of our new model • The score of our new model which incorporated some more features came out to be be 0.83 with the mean square error being 2.1501 which is quite satisfactory for a linear regression model

Conclusion • From these insights, we can derive that if we are working on more relevant features and are thoroughly equipped with the domain knowledge of the subject, we can successfully build models which are highly accurate and reliable. • Thus we are able to successfully predict the price of a car based on the selected features and attributes like company, model, transmission type etc.

Scope for future work

• This project can be further amplified by incorporating the use of Neural Networks to assess other features like paint wear-off, visual conditions of the interior etc. • More data can be used to increase the data points for more accurate training of the model. • Lastly, the developed model can be deployed as a web application using python frameworks like Flask or Django.
