# CH5019: Mathematical Foundations of Data Science

This repository contains the code files and report for the term project of CH5019.

__Question 1:__

Grayscale images of 15 subjects under 10 different conditions were obtained and are
given in the file Dataset_Question1. Due to storage limitations, only one representative image can be stored for each subject in the database for future automated facial recognition purposes. Perform SVD on all the images for a subject to identify characteristic features that will be stored for each subject. Only this information should be used in the future automated facial recognition tasks. In the report, please show the representative images of all the subjects. Given an image, the facial recognition method is based on the smallest norm between the image and the representative imagesin the database. Determine the number of images out of 150 that you are able to correctly identify based on this approach in terms of accuracy. MATLAB image processing functions or python image processing libraries are not to be used for this assignment.

__Question 2:__

This data set describes operating conditions of a reactor and contains class labels
about whether the reactor will operate or fail under those operating conditions. Your job is
to construct a logistic regression model to predict the same.
Dataset_Question2.xlsx: The data contains a 1000 X 6 data matrix. The first five columns are
the operating conditions of the reactor. The sixth column provides necessary annotation:

- Temperature: 400-700 K
- Pressure: 1-50 bar
- Feed Flow Rate: 50-200 kmol/hr
- Coolant Flow Rate: 1000-3600 L/hr
- Inlet Reactant Concentration: 0.1-0.5 mole fraction
- Test: fail/pass. Whether the reactor will operate or fail under the corresponding operating conditions.


Using the given datasets, make a report on the following:

1. Describe the statistics of the data.
2. Partition your data into a training set and a test set. Keep 70% of your data for training
and set aside the remaining 30% for testing.
3. Fit a logistic regression model on the training set. Choose an appropriate objective
function to quantify classification error. Manually code for the gradient descent
procedure used to find optimum model parameters. (Note: You may need to perform
multiple initializations to avoid local minima)
4. Evaluate the performance of above model on your test data. Report the confusion
matrix and the F1 Score.

__Question 3:__
Coronaviruses are a large family of viruses which may cause illness in animals or
humans. In humans, several coronaviruses are known to cause respiratory infections ranging
from the common cold to more severe diseases such as Middle East Respiratory Syndrome
(MERS) and Severe Acute Respiratory Syndrome (SARS).
The number of new cases are increasing day by day around the world. The ICMR dataset has
information from the states and union territories of India at daily level.


Using the given datasets, make a report on the following points: 

1. Which age group is the most infected?
2. Plot graphs of the cases observed, recovered, deaths per day country-wise and statewise.
3. Identify the positive cases on a state level. Quantify the intensity of virus spread for
each state.
 Intensity here means number of positive cases/population density.
4. List places in the country which are active hotspots/clusters as on 10.04.2020.
Hotspot is defined as an area in a city where 10 or more people have been tested
positive.
5. Which states have the maximum change (consider increase and decrease separately)
in number of hotspots on weekly basis from 20.03.2020 to 10.04.2020 (3 weeks).
6. For the given data, identify cases with international travel history (primary case),
personal contact with primary case (secondary case). Cases which do not fall in the
primary and secondary fall into tertiary case. Quantify them based on the percentage
for the top 5 states with maximum cases till 10.04.2020.
7. Find out the number of additional labs needed from the current existing labs (assume
100 tests per day per lab) with an increase rate of 10% cases per day from 11.04.2020
to 20.04.2020. List out any further assumptions considered.
8. Plot the number of cases starting from 1st March - 10th April. Based on this plot can
you comment on the popular notion of ‘flattening the curve’.
9. As we know,social distancing isthe best option to avoid the spread. Based on the time
series data (covid_19_india.csv), can you suggest how successful the 21 days
lockdown has been?




