The purpose of this analysis is to develop a predictive model that can assist the nonprofit foundation, Alphabet Soup, in selecting applicants for funding who are most likely to succeed in their ventures. Given the limited resources and the importance of maximizing the impact of their funding, Alphabet Soup aims to use this tool to make data-driven decisions, ensuring that their investments yield the highest possible success rates.

---------------------------------------------------------------------------------------------------------------

Data Preprocessing Questions:
What variable(s) are the target(s) for your model?
The target variable is IS_SUCCESSFUL.

What variable(s) are the features for your model?
The feature variables include APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, and ASK_AMT.

What variable(s) should be removed from the input data because they are neither targets nor features?
The columns EIN and NAME were removed as they are unique identifiers that do not contribute to the model.

---------------------------------------------------------------------------------------------------------------

Compiling, Training, and Evaluating the Model:
How many neurons, layers, and activation functions did you select for your neural network model, and why?
The initial model had 36 neurons in the first layer and 16 neurons in the second layer, both with relu activation functions. The output layer had 1 neuron with a sigmoid activation function.

Were you able to achieve the target model performance?
Yes, the optimized model achieved the desired result of 75% just barely. Further optimizations could be applied to ensure the results do not fluctuate above and below the desired 75%

---------------------------------------------------------------------------------------------------------------

The initial model yielded the following results:
Accuracy: 0.7335
Loss: 0.5482

The Optimized model yielded the following results:
Accuracy: 0.7545
Loss: 0.4937

To further improve the prediction accuracy, I recommend exploring different machine learning models such as Random Forests.
