# Answer-Extraction-ASSIP-

## The data we used in the program is in the data folder.<br/>
For our data, we used the train file from SQuAD to train the model, and the dev file to test the model.
We also have two files called resolvedTexts and resolvedTexts_test, which were used to train and test the model with the coreferences resolved.
The csv files map the entities to which document and paragraph they were used in, and whether or not they were in the SQuAD answers.

For our results, we measured the accuracy in the number of entities classified correctly out of 13,577. To test the model, we varied the number of neighbors.

![ASSIP Results](ASSIP%20Results.png)
# yt
