## Data Comprehetion
- is target continous or categorical?

- figure out what a 'row' represents?

- comprehend all the features.


## Data Clean

- Missing values
    no missing values 

- Data Types
    All floats and ints, no obj

- Outliers

- Duplicates 

- Check for data integrity


## Data Preparation

- Drop 'Unnamed'Column

- replace whtie spaces in column names 


## EDA

- see if there are relationships between variables to use to create other variables 
    - categories of variables and see if the distributions clump         together is pecific ways 
    
        - if so bin them 
        
    - loot at scatterplots  of continuous variablews 
    
        - if ther eare groupings int hose scatter plots, bin c               categorical variables 
        
         -if there are trends inteh scatter plots we can trasform            the variables in
             - if we see a exponetial curbe, we can create a new                  variablew taking the log, etc


## Modeling

- split into train/test sets 

- pick classification models to run
    -logistic regresson 
    -KNN 
- run cross_validation precess for initial models  for each of the above to get a baseline for how the models do 
       - fit x_train to model 
       - generate predictions
       - generate metrics of                  predictions agains actual            values
       -look at recall, becasue we           wasnt to select rteh models           that do best at minimizing            negatives 
       -generate both training and testing metrics through corss validation
       


## Final analysis interpretation