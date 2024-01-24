# Deep-Learning-Challenge
Module 21

**Analysis Overview ** The purpose of the analysis to create and evaluate a model capable of predicting whether an application for funding should be accepted or rejected. The model uses existing data showing what contributed to success versus failure previously. A model is then created that can predict uwhether future funding requests should be acceptable or rejectable in the future.

**Results ** 
1. The target variable is "IS_SUCCESSFUL."
2. There are a lot of features in this data including application type, affiliation, classification, organization, income, special considerations, status, and requested amount.
3. The EIN and NAME variables were removed because they were not useful in generating a predictive model.
4. My initial model had 2 hidden layers, each with 6 neurons. Both hidden layers used relu activation. The second model attempt, which was the final model selected, had each layer wiht 16 neurons, but still had 2 hidden layers and used relu activation.
5. I attempted 4 different variations on the model. The second model showed the best accuracy. It did not reach the suggested cutoff of 75%. Its accuracy was 73.2%.
6. To improve the model, I first added neurons. That improved the model some. Then I added epochs, and the accuracy dropped. Finally, I tried adding a third hidden layer, and the accuracy dropped to the lowest of the attempts. 

**Summary ** The model unfortunately did not show acceptable accuracy. Improving accuracy may benefit from some rebinning of classification and/orapplication type. There also could be some factors in the model that aren't very predictive that may be suppressing the accuracy of the model. 

**File Location ** The key file for this assignment starter_code.ipynb can be found in the starter_code folder of the repository.

**Syntax Sources ** Learning assistants helped me figure out how to create the binning for the first feature, and helped me fix an error I was getting with my dummy codes. I also used an outside source to work out the value counts step of the assignment: https://re-thought.com/pandas-value_counts/.  All of the remaining code was self-generated or was copied and altered from class material.
