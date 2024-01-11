# code_collab
Final Projet in Machine Learning


11-01-2023

ML_1_Stat_Desc --> Descriptive stats of our variables from learn dataset.
ML_2_Model --> I tried 2 models and compare their performance without using hyperparameters (Random Forest, Logistic Regression). Results are quite similar at this stage.
ML_3_Categories --> I just tried to see what kind of categories we had in the learn dataset to better encode these variables.
ML_Merged_ --> I made several attempts to see how to merge the data and handle missing values.

please don't work on these, they are just here in case we need some code for our Main_ file.

At this point, without having run the main_ file, we are at 80% accuracy using random forest. For logistic regression in ranges from 70 to 80 depending on the dataset.

Next steps:

1) Priority:
- Maybe explore other binary classifiers (maybe use a neural network ?)... 
- ... while using hyperparameters and GradientDescent to better tune our models. *** (see the end for guidance)
- Check if we should use a specific technique to give more weight to the target G than B (bc we habe 61% of B and 39% of G)

2) Next Level:
- After this, the goal would be to write a code that is as efficient as possible (meaning creating functions to declutter the code). And then start creating the best pipeline possible before feeding our model.
- Since the code is quite repetitive between models, we should be able to automate that. It also means that we have to be cautious with the code because it will take longer to run.
