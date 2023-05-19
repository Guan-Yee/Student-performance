# Student-performance

<p align="justify">
This dataset is retrieved from the UCI Machine Learning Repository. The students' scores are obtained from 2 schools in Portugal. This project aims to find the siginficant predictors that will affect the *G3* score. Firstly, the iterative Mutual Information is performed, and 11 features with non-zero mutual information are stored in the *x_train_clean_11.csv* and *x_test_clean_11.csv* files. Then, Random Forest, LGBM, XGBoost, and CatBoost Regressor are trained on the *x_train_clean_11.csv* dataset. The LGBM Regressor achieves the best adjusted R-squared score of 83.72%. Lastly, the *G1_G2_sum*, *failures*, *age*, *Mjob*, and *subject* columns are identified as significant predictors that determine the students' *G3* final scores.
</p>

## References
* [P. Cortez and A. Silva, 2008] P. Cortez and A. Silva. Using Data Mining to Predict Secondary School Student Performance. In A. Brito and J. Teixeira Eds., Proceedings of 5th FUture BUsiness TEChnology Conference (FUBUTEC 2008) pp. 5-12, Porto, Portugal, April, 2008, EUROSIS, ISBN 978-9077381-39-7. [Web Link](http://www3.dsi.uminho.pt/pcortez/student.pdf)