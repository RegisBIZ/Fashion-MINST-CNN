# To build convolutional neural network model and Linear Regression model requires the following fundamental skills:
**install PyTorch library**
**Knowledge in how to use NumPy, Pandas and Sklearn**
**Have fundamental knowledge of linear algebra**
**Skill of how to formulate optimization problem of function and how to minimize it**
## My observation on Linear regression model 
The test accuracy of my model is 0.6906509711862155 with Mean Square Error is 26.810465286940563 before applying regularization techniques.
The Test accuracy by exercising Ridge Regression is 0.69084 with Optimal Alpha: 46.41588833612773 and Mean Square Error:26.79363458512451.
The test accuracy by exercising Elestic Net is 0.6906572702135808 with Optimal Alpha is0.021544346900318832 and Optimal L1 Ratio is 0.7000000000000001 and then MSE is 26.80991936683483
## Decision
**Ridge Regression** has a slightly better ** MSE (26.7936)** and **R² (0.69085)**. Ridge Regression performs best among the three.It slightly reduces MSE compared to Linear Regression.
