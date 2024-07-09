Module 21 Challenge
Submitted by: Justin Bein
UC Berkely Data Bootcamp
January 2024 Cohort


In this challenge I’ll be given a CSV containing more than 34,000 records of organizations that received funding from Alphabet Soup. I am tasked with building a deep learning model to evaluate the applicant records and predict whether an applicant will be successful if funded by Alphabet Soup.

Source Data:
The source data is imported from
 "https://static.bc-edx.com/data/dl-1-2/m21/lms/starter/charity_data.csv"

Approach
Several libraries (sklearn, StandardScaler, pandas, tensorflow, etc.) were imported.
Exploratory data analysis was undertaken to evaluate the features and target of the model.
Preprocessing was completed to simplify the data and reduce the dimensionality.
A model was defined (including the number of layers, neurons, and activation models), trained and evaluated.
After evaluating the initial model, a new model was created and additional features were added. Similar preprocessing was undertaken, followed by model definition, training, and evaluation. The new model showed improved results and the target accuracy (75%) was reached.

Note: I pushed several iterations of the model to my repo. The final files containing my work and results:

Starter_Code.ipynb  (contains the original model)
Starter_Code.ipynb  (contains the weights of the original model)

AlphabetSoupCharity_Optimization.ipynb (the optimized model)
AlphabetSoupCharity_Optimization.ipynb (contains the weights of the optimized model)
