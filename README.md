# LSTM_Predictor
Using various deep learning models to predict stock prices.

## Methods employed:
LSTM deep learning model
The libraries used:
Keras
Tensorflow
numpy
pandas
hvplot
matplotlib

# Steps to be taken:

1. Join the data into a single DataFrame
2. Create a function to create variable X and y.
3. Predict Closing Prices using a 10 day window of previous fng values
4. experiment with window sizes anywhere from 1 to 10 and see how the model performance changes 
5. I will Use 70% of the data for training and the remainder for testing
6. Scale my data
7. Reshape the features
8. Build my LSTM model
9. Compile
10. Train model
11. Run performance analytics.


## Questions to be answered:
**Which model has a lower loss?**
**Which model tracks the actual values better over time?**
**Which window size works best for the model?**


## Conclusion:

**Which model has a lower loss?**
The model using sentiment/ FnG_value had a lower stop loss using a window of 5. 

**sentiment:**

window 5 = .033 loss
window 10 = .037 loss

**Closing prices:**
Window 5= .049 loss
Windown10 = .061 loss

**Which model tracks the actual values better over time?** 
The sentiment value tracks values better over time. the model starts March 2019 and by July 2019 the real and predicted prices start overlapping some what.

**Which window size works best for the model?**

As previously stated a window size of 5 works best.

## Plots

![Alt text](relative/path/to/img.jpg?raw=true "Title")
![Alt text](relative/path/to/img.jpg?raw=true "Title")
