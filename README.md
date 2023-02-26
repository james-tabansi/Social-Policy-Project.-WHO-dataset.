## Context:
- DeltaSquare is an NGO that works with the Government on matters of social policy to bring about a change in the lives of underprivileged sections of society. They are tasked with coming up with a policy framework by looking at the data government got from WHO. You as a data scientist at DeltaSquare are tasked with solving this problem and sharing a proposal for the government.

## Problem Description:
- Certain people in Society are under stringent living conditions and one of the ways to ease their struggle for sustained livelihood is by implementing the appropriate social policy. A sustainable future is dependent on the type of social policy that will be implemented based on the insights and recommendations from this project.

## Objectives of the Project:
- The dataset aims to answer the following key questions:

    * What are the different factors that influence the income of an individual?
    
    * What insights will guide the government in structuring an appropriate policy framework that will augment living conditions of the underpriviledge sections of society.
    

    * Is there a good predictive model for income that exists?
    
    * What does the performance assessment look like for such a model?
    
## Model and Metrics
- The project seeks to classify any individual based on his or her income as either priviledged or underpriviledged hence, it is a classification problem and would require a classification model.
- Both Logistic Regression and Tree Based models will be used and the best model will be selected based on their performance.


- More focus will be at identifying an underpriviledged person correctly. This is because there is little problem in identifying a rich man as a poor man. however, it is a problem to classify a poor man that is sufferring as a rich person as he or she may not be able to recieve the help they want if our policy recommendations were implemented because they will be treated as people who do not need such help.
    - people with lower salary will be termed underpriviledged and classified as 1
    - people with higher salary will be termed priviledged and classified as 0
- therefore, efforts will be at reducing incorrectly classified 1s as 0s. This means I will aim to increase the recall of my model.
