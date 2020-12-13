# Neural Network Charity Analysis
## Overview 
### Purpose
The purpose of this analysis is to create a binary classifier to be able to predict if an applicant would be successful if funded by Alphabet Soup. The charity dataset contained over more than 34,000 applicants and organizations, giving us plenty of data to work with machine learning and neural networks. We used a Jupyter Notebook to read in the data, cleaned, and preprocessed it before continuing on to split it into test and training data. We then scaled it before using the StandardScaler. Training the data using neural networks, we could use many different layers in order to come out with the most accurate and reliable data.

 ## Results
### Data Preprocessing

- What variable(s) are considered the target(s) for your model?
The target for our model would be the 'IS_SUCCESSFUL' column of our charity_data.csv. This column is represented by 0 and 1's or no's and yes's to see if that particular applicant was a success by being funded by Alphabet Soup. 

- What variable(s) are considered to be the features for your model?
The following were the variables to be considered:

1. APPLICATION_TYPE—Alphabet Soup application type
2. AFFILIATION—Affiliated sector of industry
3. CLASSIFICATION—Government organization classification
4. USE_CASE—Use case for funding
5. ORGANIZATION—Organization type
6. STATUS—Active status
7. INCOME_AMT—Income classification
8. SPECIAL_CONSIDERATIONS—Special consideration for application
9. ASK_AMT—Funding amount requested

- What variable(s) are neither targets nor features, and should be removed from the input data?
The variables that were not considered were the 'EIN' and 'NAME' columns. Because they were just identication columns and not really needed, they were able to be removed. Being an identifier column could not provide any insight if the future applicants would be successful or not. 

### Compiling, Training, and Evaluating the Model

- How many neurons, layers, and activation functions did you select for your neural network model, and why?
I used two phases of training the data. Within the first training, I used three layers
- Were you able to achieve the target model performance?
- What steps did you take to try and increase model performance?

