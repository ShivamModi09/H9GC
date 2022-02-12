# H9GC
Team Members: Akash Yadav, Arpit Sahu

## Approach and Significance of y
We saw the trend in the data that if y is 1 then Close is greater than Open for next day. So we checked it using Logistic regression and we got confident about our observation. So y here simply signifies the same.
If y=1, it is safe to invest next day or else, there is loss in buying stock next day.

### Model Details
As this was a simple Logistic regression, we can show it as: y = {if sigmoid(slope\*Change + intercept) > 0.5, then 1 else 0}. So, the weights can be given as: slope = 10.30810683 and intercept = -0.16092236. 
