# Absenteeism

### This is a case study to determine the probability of an employee being absent excessively.
### Step-1: Preprocessing
Data imported from *Absenteeism_data.csv* is preprocessed and after preprocessing it is saved into *'Absenteeism_preprocessed.csv'*.<br>
The code for preprocessing is in 'Absenteeism_Preprocessing.ipynb'.
### Step-2: Model fitting
The preprocessed data is then imported in *'Absenteeism_Logistic_Regressionn.ipynb'*. A little preprocessing like setting the targets, test train split etc is done. Logistic Regression model is used to fit the dataset.
### Step-3: Summary table
Summary table is created for the coefficients and the intercept and the model is then discussed.
### Step-4: Saving the model
The logistic regression model and standard scaler are pickled for further use.
### Step-5: Module deploy
Using the code for logistic regression, a local module is created in *'absenteeism_module.py'* (in folder: *'module_testing'*) and is used to predict the absenteeism for a new dataset *'Absenteeism_new_data.csv'*. The predictions are saved along with the inputs in a csv file *(Absenteeism_predictions.csv)*.<br>
The code for this is in *'Absenteeism Integration.ipynb'*
### Step-6: Visualization in Tableau
The predictions for the new dataset is visualized in Tableau. The effect of different reasons, children, distance from home on the employee being absent are visualized *('Absenteeism_Predictions_Visualization.twbx')*.
