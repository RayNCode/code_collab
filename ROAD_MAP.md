# code_collab
Final Projet in Machine Learning


30-12-2023

ML_1_Stat_Desc --> Descriptive stats of our variables from learn dataset.
ML_2_Model --> I tried 2 models and compare their performance without using hyperparameters (Random Forest, Logistic Regression). Results are quite similar at this stage.

!! I can't run the notebooks in collab because the CSV is not linked to them. I don't know how to circumvent this issue.

ML_3_Categories --> I just tried to see what kind of categories we had in the learn dataset to better encode these variables.

Next steps:

1) Priority:
- Create another notebook with strategies to merge and manage missing values of other csv files.
  We can start merging one dataset at the time.
- Maybe explore other binary classifiers (as explained in the ML_2_Model towards the end)...
- ... while using hyperparameters and GradientDescent to better tune our models. *** (see the end for guidance)
- Check if we should use a specific technique to gibe more weight to the target G than B (bc we habe 61% of G and 39% of B)

2) Next Level:
- After this, the goal would be to write a code that is as efficient as possible (meaning creating functions to declutter the code). And then start creating the best pipeline possible before feeding our model.
- Since the code is quite repetitive between models, we should be able to automate that. It also means that we have to be cautious with the code because it will take longer to run.



***Integrate hyperparameter selection from the start:
- Use GridSearchCV or RandomizedSearchCV with cross-validation to automatically find the best hyperparameters for your model, integrating this search into your modelling pipeline for robust evaluation and selection.
- Evaluate systematically: Ensure that any model evaluation, including hyperparameter selection, is done using resampling techniques such as cross-validation to prevent overfitting and ensure that the model generalises well to new data.
- Automation and consistency: Create a consistent pipeline that includes pre-processing, hyperparameter selection and model training, enabling efficient automation and reducing manual errors, while improving the reproducibility of our results.
