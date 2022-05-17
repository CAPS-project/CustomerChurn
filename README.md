# CustomerChurn
This module is all about the probability that whether customers will still continue with the bank or any organization.
#STEPS
1. Initially cleaning the CSV file, and checking the empty value, Since none was empty, So dropping the irrelevant columns that will not affect the result at all.
2. Then preprocessing and encoding the categorical data, which creates a dummy variable for categorical data, as it makes prediction easier.
3. then with the help of the target class which is exited, finding the people leaving the bank or not, where if plotted it would be divided into two categories 0 and 1.
 where 0 signifies the customer would stay with the bank and 1 would show the customer leaving the bank.
4. then following the regular procedure of splitting the dataset into tests and training, for accuracy.
5. Creating a model in TensorFlow and using relu and sigmoid function as sigmoid is normally for one of the two outputs.
6. With 100 epochs, take one sample with the highest accuracy.
7.predicting the accuracy score of the data and plot it.
8. As val_acc is not above accuracy in the plot so it's not overfitted, model.
