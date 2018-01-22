## Breast Cancer ( 1 = Malignant(M) vs 0 = Benign(B) ) 
### Breast cancer dataset 
This dataset consists of 10 features whose values are obtained in terms of Mean, Standard error and worst case.
First two columns gives us the information about ID and The output itself (Malignant or Benign).

**Instruction for data-preprocessing**
- First load the data.csv file to dataframe.
- Then divide it to test and train dataset in 80:20.
- Normalize the data i.e. feature normalization.

### Normalization
Find out the mean and standered deviation for each column and substract each element from its mean and divide this by its standered deviation.

### Algorithm for logistic regression
**Steps**
- random initialization of w and b
- Forward propogation
- Backward propogation
- gradient descent

### Sigmoid function
This function is required for calculating the hypothesis i.e. y = a = sigmoid(z)
where z = w^TX + b

### Forward and backward propogation
hypothesis in logistic regression is y = a = sigmoid(z) = sigmoid(w^TX + b)
