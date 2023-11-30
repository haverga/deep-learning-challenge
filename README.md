# deep-learning-challenge

# Overview:
- The purpose of this Analysis is to help Alphabet Soup identify the applicants that have the best chance at succeeding in their ventures.

# Results:
- Data Preprocessing:
- Target variable used: "IS_SUCCESFUL"
- Feautured variables used: All but EIN and Name

- Compiling, Training, and Evaluating the Model:
- NUMBER Neuron, Number Layers, Activation functions: relu and sigmoid. 
- Not able to hit mark.
- increased, decreased number of neurons, layers and changed functions.

# Summary
- Attempted adding another hidden layer, to optimize accuracy. No noticeable improvement, remained at 72%
- Attempted doubling epochs from 100 to 200, to optimize accuracy. No noticeable improvement, remained at 72%.
- Attempted combining both of the above. No noticeable improvement, remained at 72%.
- Tried removing columns "SPECIAL_CONSIDERATIONS" and "USE_CASE". No noticeable improvement, remained at 72%.
- Best result I got was that of 72.67% which resulted from adding more neurons to the the first layers and the hidden layers. And using relu in the first and hidden layers and sigmoid in the output layer.
- I was not able to duplicate the 72.67% after I made attempts to improve it. And when I reverted the changes to the formula code that gave me the 72.67, it gave me a different result.

# Coclusion
- ~72% accuracy in the model is as good as it could get trying the above optimization options.
- Next option I would try to Optimize the model would be to run an auto_optimization "keras tuner".

