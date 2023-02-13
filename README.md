# Highly-Imbalanced-data-on-multiclassification
Analyze and predict the candidate completion based on Highly imbalanced sample data set on multiclassification output


Project objective: Teach for America(TFA) continuously studies and refines the admissions process to select those who will have the most impact, to improve corps completion, and to increase matriculation. In this analysis, I will focus on the preliminary study on how each level affect the completion in each funnel of application process.

Application to admission process consists of 6 main funnels:
1) Interview invites
2) Complete interview
3) Accepted to corp.
4) Confirm offer by candidate
5) Start first day
6) Complete program

Method and tools overview::
1) Correlation matrix
2) Clustering analysis
3) Imbalanced handling via SMOTE-Tomek
4) Predictive model via ExtraTree classification for multiclass
5) Feature importance from predictive model

The first part of the project will involve the Correlation and Clustering analysis which will be included in this paper. Then, the predictive model will be conducted from the results of Clustering analysis as the result of this paper.

For Predictive model, I aim to identify and predict the new candidate who has a potential to complete year2 of the program. With this goal, I will cover the candidate beyond the invited interview status, in other words, I will take into account all the applicant data points in order to predict and evaluate the candidate profile. In terms of model, since the outcome will include 3 classes; 0,1,2 or 'Incomplete','In process' and 'Completed', we're dealing with multiclassification model. Moreover, covering the entire data set without any transformation would create a bias in prediction model, so, in this document, I will also cover the handling of highly imbalanced data set as a preparation for predictive model.
