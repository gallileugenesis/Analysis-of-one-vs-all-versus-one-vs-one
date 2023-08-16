# Analysis of one-vs-all versus one-vs-one approaches in lithofacies classification


*Abstrct* 

The lithofacies classification provides valuable information about the geological history and the depositional environment. For multiclass classification tasks, as is usually the case with lithofacies classification, there are two basic approaches for building the models: the One-vs-One (OvO) and the One-vs-All (OvA) approaches. In general, when building models, default settings are typically employed, without conducting a detailed study to determine the most suitable approach for each scenario. In this study, we evaluated the performance of the OvA and OvO in the lithofacies classification task. The results indicate that the OvA model has lower computational cost and consistently outperforms the OvO model across almost cross-validation folds. Results on test data indicate that OvA can be a good alternative in scenarios with imbalanced classes or when there is a limited amount of data for training and testing. The OvO model can be an interesting alternative when the imbalance between classes is an important factor for the problem.

