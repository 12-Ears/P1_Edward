# P1_Edward - 23220451

## SVM version 1 (05.1)
Dilemma    : whether to use univariate models or multivariate.
Conclusion : univariate models correspond to which frequency correlates the most to the target variable. Our solution should be more complex than that, hence multivariate should be used.

## SVM version 2 (05.2)
Goal       : explore sampling methods to balance out the dataset.
Conclusion : SMOTE, SMOTETomek and SMOTEENN performs good. Pick out another undersampling. Although, the results are all too good for some reason.

## SVM version 3 (05.3)
Dilemma    : whether to use other variables besides frequencies to make the prediction.
Conclusion : Only frequencies should be used. This was discussed and confirmed by the client as well.

## SVM version 4 (05.4)
Goal       : explore feature selection methods.
Conclusion : while wrapper methods such as SFS and RFE "might" provide better results. They take insanely long to run, and so I have chosen to focus on embedded feature selection.

## SVM version 5 (05.5)
Goal       : put all chosen sampling, feature selection methods with SVM to solve project objectives.
Conclusion : Done.