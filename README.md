### Feature-Engineering-Model-Tuning

**Introduction:**

* In semiconductor manufacturing, monitoring signals from sensors and process measurement points is crucial.
* However, not all signals are equally valuable; some contain useful information, while others are noise.

**_Data Description:_**

* Dataset: signal-data.csv (1567, 592)
* Each data point represents a production entity with 591 features and a pass/fail yield label.
* Pass is represented by "-1" and fail by "1".

_Project Objective:_

* Build a classifier to predict pass/fail yield and analyze feature relevance.

_Steps and Tasks:_

**Import and Understand Data:**

* Import 'signal-data.csv' as DataFrame.
* Print 5-point summary and make observations.

_Data Cleansing:_

* Remove features with 20%+ null values and impute rest with mean.
* Drop features with the same value for all rows.
* Drop other irrelevant features.
* Check for multicollinearity and take necessary action.
* Make logical modifications to the data.


_**Data Analysis & Visualization:**_

* Perform detailed univariate analysis.
* Conduct bivariate and multivariate analysis.

_Data Pre-processing:_

* Segregate predictors vs. target attributes.
* Check for target balancing and fix if imbalanced.
* Perform train-test split and standardize data if required.
* Ensure train and test data have similar statistical characteristics.

_**Model Training, Testing, and Tuning:**_

* Train a model using supervised learning technique.
* Apply cross-validation techniques.
* Perform hyper-parameter tuning for best accuracy.
* Utilize techniques like dimensionality reduction, attribute removal, etc., to enhance performance.
* Display and explain classification report for each model.


_**Post Training and Conclusion:**_

* Compare models based on train and test accuracies.
* Select the best-trained model and provide detailed justification.
* Pickle the selected model for future use.
* Conclude findings and results.

**Conclusion:**

* The project aims to predict pass/fail yield in semiconductor manufacturing using machine learning techniques.
* Through data analysis, cleansing, and model training, the most relevant features are identified to enhance model accuracy.
* The selected model is pickled for future use, providing a robust solution for yield prediction in semiconductor manufacturing.
