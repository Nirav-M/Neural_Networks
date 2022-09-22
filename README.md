# Neural_Networks_Challenge

The purpose of this challenge was to create a machine learning model to predict whether the startup companies that apply for funding from the venture capital firm Alphabet Soup will be successful or not. 

Given a csv file containing information about more that 34,000 companies that recieved funding from Alphabet Soup, the first step was to preprocess the data. This was achieved by encoding the file's categorical variables into multiple columns with either a 0 or 1 value to support the binary classification model, using the OneHotEncoder function. Next the data was split into train and test data using the train_test_split function, and scaled using the StandardScaler function. 

Following the preparation of the data, three neural networks were created using the Sequential model, and their performance tested by calculating the loss and accuracy of the model. Although the models differed slightly, all three had an accuracy score around 0.73 and a loss of approximately 0.55. Finally, all the models were saved in the resources folder as a HDF5 file. 
