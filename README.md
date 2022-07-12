# Neural_Network_Charity_Analysis
 
<b>Overview of the analysis:</b><br>

The purpose of this project was to create a binary classifier for the client to sort through 34,000 organizations and make predictions of success or failure based on whether or not they were funded by Alphabet Soup.

<b>Results:</b><br>
<i>What variable(s) are considered the target(s) for your model?</i><br>
The variable that was considered the target for the model was the ‘IS_SUCCESSFUL’ column.

<i>What variable(s) are considered to be the features for your model?</i><br>
The variables that were considered the features for the model were all of the columns besides the ‘IS_SUCCESSFUL’ column. 

<i>What variable(s) are neither targets nor features, and should be removed from the input data?</i><br>
The variables that were neither targets nor features were the columns that were dropped when creating the model. 

<i>How many neurons, layers, and activation functions did you select for your neural network model, and why?</i><br>
I chose to use two hidden layers with 24 neurons in one and 12 neurons in the other, as well as the ‘relu’ and ‘sigmoid’ activations, because this is the same setup as the weekly module work. 

<i>Were you able to achieve the target model performance?</i><br>
No, the models did not reach 75%.

<b>Attempt 1</b><br>
<img width="702" alt="Screen Shot 2022-07-12 at 12 21 52 PM" src="https://user-images.githubusercontent.com/100445222/178544845-f5821ab9-bbe3-4780-b815-e88528ff6b05.png">

<b>Attempt 2</b><br>
<img width="704" alt="Screen Shot 2022-07-12 at 12 30 00 PM" src="https://user-images.githubusercontent.com/100445222/178545016-047bbdd7-5c73-494e-aa3e-e387bc5aa4d0.png">

<b>Attempt 3</b><br>
<img width="727" alt="Screen Shot 2022-07-12 at 12 30 26 PM" src="https://user-images.githubusercontent.com/100445222/178545092-c97245ea-703d-46f5-b89b-4a0074294cdd.png">


<b>Summary:</b><br>

With a final accuracy score of 73%, I believe the model could yield better accuracy results if one more feature is removed to allow for the 2% deficit. 
