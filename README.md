# deep-learning-challenge

## Overview/Background:
The nonprofit foundation Alphabet Soup wants a tool that can help it select the applicants for funding with the best chance of success in their ventures. With your knowledge of machine learning and neural networks, you’ll use the features in the provided dataset to create a binary classifier that can predict whether applicants will be successful if funded by Alphabet Soup.

## Results:

### Data Preprocessing
Here we read in the .csv file and removed unnecessary columns, EIN & NAME.  These columns were removed because they would not be necessary for helping the model in its predictions.  All other data was featured.

### Compiling, Traning, and Evaluating the Model - 
For my optimization attempts, I originally used two nodes in my Neural Network and the 'relu' activation tool.  This generated an accuracy of 72.54%.  On my second attempt I did all the same except this time, I used three nodes in my Neural Network.  This increased accuracy to 73.01%.  So I stuck with the three nodes for the rest of my optimazations.  In my third attempt, I added the validation_split function when training the model.  At 15%, this led to a slight decrease in accuracy to 72.93%.  Finally, I removed the validation_split and tried out activation 'tanh' when defining the Neural Network.  This also led to a decrease in accuracy to 72.87%.  Unfortunately,  I was not able to reach the 75% accuracy goal in my attempts.

## Summary:
Overall, there was a lot to do for this assignment, there are any number of combinations of nodes and activations that you could use for this project.  I am sure there is a program out there that can optimize this process.  But from my experience on this assignment, I found that 3 nodes in the Neural Network were optimal.  In the future I would experiment more with Activations like 'tanh' and 'sigmoid'.