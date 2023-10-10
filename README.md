# deep-learning-challenge
ANALYSIS:
When beginning to code, I wanted to create a learning model to see if we can predict what ventures will have success with the nonprofit foundation Alphabet Soup. 

RESULTS:

-Data Preprocessing:
  -The variable I targeted within the dataset was "IS_SUCCESSFUL"
  -The variables I used initially were "AFFILIATION", "CLASSIFICATION", "USE_CASE", "ORGANIZATION", "STATUS", "INCOME_AMT", "SPECIAL_CONSIDERATIONS", "ASK_AMT"
  -Initially I dropped "EIN" and "NAME"

-Compiling Training and Evaluating the model:
  -I used 2 layers, with a total of 192 neurons. I used relu as my activation functions for the hidden layers and for the output layer I used sigmoid.
    -I chose 2 layers to start to see how the model processed the data. The activation functions were used because of my familiarity with them.
  -I was not able to acheive the target model performance. 
  -I increased the amount of hidden layers, dropped columns, binned the features and changed the activation functions.

SUMMARY:
The results of the deep learning model were very disappointing. High loss and accuracy lower than 75%. I think if we used an unsupervised learning model we should see better results. Letting the machine create the clusters can help us check if we can predict what the Charity is asking for. 
