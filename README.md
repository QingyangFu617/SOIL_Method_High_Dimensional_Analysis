# SOIL_Method_High_Dimensional_Analysis

This Project is an interpretation based on Paper: https://arxiv.org/pdf/1608.00629.pdf
 

Variable importance measure is one constrictive approach to improve the reliability and reproducibility in choosing models for high-dimensional linear regression. It can help to identify which variables are essential and which are not for further estimation and prediction. The benefits of using it include saving time and cost due to the reduction of variables to be considered, helping decision-makers gain a more comprehensive understanding, providing a ranking of variables to balance the model selection and model averaging procedure, etc.


There are many importance measures with parametric models available now. One of the methods is based on a final selected model like t-test value and p-value, but it could lead to the problem of “winner takes all” since unselected variables would have zero importance. There is another approach based on the R2 decomposition, and some scholars have proposed several methods such as dominance analysis (Budescu 1993), information criterion-based method (Theil & Chung 1988), and hierarchical partitioning (Chevan & Sutherland 1991). 


There are also available non-parametric methods, and the random forest is the one that has been used in many fields for regression and classification. Although the random forest has a much lower overfitting risk than decision trees, this problem still exists. Due to the large number of trees considered, the computation may be far more complex than other algorithms.


In the paper, the author proposed a new approach called SOIL, and it has some beneficial features or advantages which can improve the procedure of data analysis. SOIL involves many candidate models for consideration which makes it more objective and reliable. It could avoid bias by using independent external weighting. Moreover, the SOIL importance measure could be naturally used for finding the best model since more critical variables for sparse modeling will receive higher importance values. 


All in all, SOIL could provide more information than the existed measures for data analysis and is helpful in different steps of the modeling procedure. Therefore, it could improve the reliability and reproducibility of data analysis when variable selection is needed.



