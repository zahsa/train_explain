# train_explain
train a CNN and explain the important features


# Why we chose Morris method?

Morris method is a derivative based method and is a promising approach which globally measures the effect of each variable. Therefore, it provides a global explainablity for the trained models. It has a reasonalbe computational cost which makes it very preferable for high dimensional datasets such as ours. It can work for continuous as well as discrete input spaces and it is suitable for our dataset which is in semi-binary format. The sampling mechanism explores the entire space and provides a global understanding throughout the whole multivariate input space. Many other methods will fail either at the sampling phase for high dimmensional parameter space or are not compatible with the particular architecture of our trained network. Morris method can provide information both about influential as well as negligible parameters. Moreover, it can group the parameters into three categories based on their levels of importance and give insight about interaction between parameters. More specifically, Morris method specifies whether one factor is important or non-important, linear or non-linear, has interaction or no interaction with other parameters. In addition, compared to other interpretablity methods, Morris method is more suitable in terms of evaluation time and accuracy. 
