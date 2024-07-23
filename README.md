Problem statement – the base dataset has information about fraud bool, name, email similarity, previous address months count, current address months count, customer age, intended amount, payment type, has other cards, source, device fraud count and so many columns. In this dataset find dependent and independent variable and write codes for random forest classifier by taking training size is 60% and remaining for testing and sampling strategy 0.6 is for under sampling and 0.7 is for over sampling and training size is under sampling and over sampling is 0.7 and remaining data for testing. check the accuracy, prepare confusion matrix and classification report.



Tools used – pandas, under sampling, over sampling techniques, random forest classifier, sklearn, matplotlib, seaborn.



Outcome – in the random forest classifier imbalanced dataset the under sampling given less accuracy 28% and over sampling given high accuracy 98%. Here predicted variable is fraud bool. 23,702 is true positive classes. 298 is false positive classes. And precision is 0.99 and recall is 1, f1 score is 0.99 is highest for no fraud category.
