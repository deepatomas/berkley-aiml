# Codio Activity 8.7: Evaluating Multiple Models 

**Expected Time = 120 minutes** 

**Total Points = 100** 

**Learning Outcome Addressed:**
Use a test set for final model evaluation

---


## Overview
This assignment focuses on solving a specific regression problem using basic cross validation with a train/test/validation split. In addition to using the methods explored, this assignment also aims to familiarize you with further utilities for data transformation including the OneHotEncoder and OrdinalEncoder along with their use in a make_column_transformer.

The operations of encoding categorical features will be introduced using sklearn. This will allow you to streamline your model building pipelines. Depending on whether a string type feature is ordinal or categorical we want to encode differently. The OrdinalEncoder will be used to encode features that do not need to be binarized due to an underlying order, and OneHotEncoder for categorical features (as a similar approach to that of the .get_dummies() method in pandas). By the end of the assignment, you will see how to chain multiple feature encoding methods together including the earlier PolynomialFeatures for numeric features

**Remember to run your code from each cell before submitting your activity.** Running your code beforehand will notify  you of errors and  give you a chance to fix your errors 
before submitting. 

### How do I open the activity?
To view the activity, click on the file `coding_activity_8.7.ipynb` in the panel on the left.

### How do I answer questions?

Throughout the activity, you will find code cells that start with:

### How do I answer questions?

Throughout the activity, you will find code cells that start with:

`### GRADED

This is a *graded* cell. In this cell, you will find the variables you will need to use to answer the questions initialized to `None`. 

Below, you will see the following code:

`raise NotImplementedError()`

If you get this error, delete the code "raise NotImplementedError()" and enter your solution to the question.

You will also see that every `### GRADED` is followed by an empty code cell. These are *autograded* cells. These cells contain the code that it's  used to check your answer.  Therefore, these cells are locked from your view.

To make sure your answer is recorded by the autograder, run **both** the graded and the autograded cells. You can do so by clicking  `shift` + `return` on your keyboard.

### How do I submit an activity?

Once you have completed the activity, save the Jupyter Notebook file by clicking the save button in the Jupyter Notebook window. Once saved, you can submit it for grading and feedback by clicking on “Education” in the menu bar at the top of the browser window and then selecting "Mark as completed". Once you mark it as complete, the autograder will grade your submission and will take you back to your dashboard. If the results are not shown in your dashboard, refresh the page and they should appear.

If you decide to go back and edit some of your answers (perhaps because you did not get full points), there are two options for doing this:
1.	From the dashboard, the activity should notate it has been graded. When you open the activity, Codio will give you the option of seeing your results or you can ‘reset assignment’. Resetting the assignment will remove all previous work and allow you to complete the assignment again.
2.	If you are already in the assignment, you can click on “Education” in the top menu bar, and then select ‘Reset Assignment’.

**IMPORTANT NOTE:** If you have trouble with the steps above, please try to reload your activity by closing the Jupyter Notebook and by reopening it using the panel on the left. Do not hesitate to contact your Program Support or your Learning Facilitator!
