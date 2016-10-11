# Reddit-Survey-Assignment-Lab
Data Science Essentials Lab CSC-570 
<br>
In 2011, Reddit did a survey of it's users. That survey can be found on the class Git repo as RedditShortDemoSurvey-1- Cleaned.csv.
Your assignment is as follows:<br>
1. Clean the survey data and conduct a full EDA. (25 pts)<br>
Aggregate all Countries to their Continents.<br>
Drop US States<br>
Look for and handle missing values<br>
Create indicator variables for categoricals, bin where you feel appropriate<br>
Clean bad data (e.g. the value movies is present in “Are you a dog or a cat person?”<br>
Visualize the distributions of cleaned variables<br>
2. Use Pearson's Correlation Coefficient, determine which variables are most highly collinear, and graph the results. (hint: http://stanford.edu/~mwaskom/ software/seaborn/examples/ many_pairwise_correlations. html) (25pts)<br>
3. Create a random forest model that predicts YOUR dependent variable based on the remaining variables.  If your dependent variable is muti-class (more than just two classes) then I'd like you to use a confusion matrix to measure model performance.  If you'd like, you may also experiment with one-vs-all AUC methods.  (50 pts)<br>
Determining YOUR dependent variable:<br>
If your Last Name Begins with A-F you will predict Employment<br>
If your Last Name Begins with G-K Marital Status<br>
If your Last Name Begins with L-P Military Service<br>
IIf your Last Name Begins with Q-Z Income<br>
