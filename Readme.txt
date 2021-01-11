# Linear classifier logistic regression from scratch


Basic Hepatitis model : File contains code for hepatitis model
Filter method model Hepatitis : Contains code for filter method on hepatitis model
Basic Bankruptcy Model : Contains code for Bankruptcy model
Filter Method Bankruptcy: Contains code for filter method on Bankruptcy model
Advanced Model: Contains code for advance model.

Run Instruction
--------------------------------------------
##. Basic Hepatitis model, Filter Method Bankruptcy ,Filter method model Hepatitis, Basic Bankruptcy Model

1. Upload the .csv file to Colab, For Hepatitis model upload "hepatitis.csv" and for Bankrutcy models upload "bankrutcy.csv".

2. The path is set as "pd.read_csv('/content/hepatitis.csv')", if you face any problem for reading the csv file, make sure that paths match.

3. To run the program execute each box one by one.

4. The results are calculated by changing the k value in class "baseModel()" and Learning rate before execution.

THERE IS A POSIBILITY THAT YOU WILL GET DIFFIRENT RESULTS, THIS IS BECAUSE OF DATA RANDOMIZATION.

## Advanced Model

1.Upload the training file and test file to Colab.

2.If there is no extra file for testing,  please select several samples in the original dataset randomly and save them as testing file, the samples remained as training file. I apologize for the inconvenience caused.

2.Run the main function with the format (train_dataset, test_dataset, alpha, lmbda, epsilon, maxiter).

3.The file name of train_dataset must be "hepatitis_train.csv", or "bankrupcy_train.csv". 

4.Alpha is learning rate, lmbda is regularization constant, epsilon is stopping criteria, maxiter is the maximum number of iterations. 

