# Neural_Network_Charity_Analysis
## Overview of the analysis
The purpose of this analysis is to predict whether or not a charity will recieve funding based on previous successes and failures. We are using a neural network to predict these outcomes.
## Results
### Data Preprocessing
- The targets for our model are to determine whether a charity will be succesful or not.
- There is 50 features and they are deterimined by APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, INCOME_AMT, and SPECIAL_CONSIDERATIONS.
- EIN and NAME column were dropped and were neither a target or feature.
### Compiling, Training, and Evaluating the Model
- I used 4 hidden layers with 200, 250, and two 150s. I did this because the first time I only did 3 hidden layers at 200 and two 150s and I thought adding another layer at 250 would help my acuuracy but it did not.
- I was unable to achieve higher than 75% accuracy.
- I added an extra layer at 250 but it didn't get to 75%.
![accuracy](https://user-images.githubusercontent.com/110861876/208533124-160d0f21-135c-4fec-992c-4752871c5fbd.png)
## Summary
I was not able to get to the threshold of 75% and I think that is because there is not enough data, but it could be possible to reach it with a lot of tweaking in the hidden layers.
