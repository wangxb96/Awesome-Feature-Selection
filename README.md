# Awesome-Feature-Selection
Feature selection, or attribute selection, is an effective data pre-processing measure that removes redundant and invalid features, thereby reducing the overhead in machine learning and statistical training while improving training results. According to [Wikipedia](https://en.wikipedia.org/wiki/Feature_selection), there are several main advantages of feature selection: simplification of models to make them easier to interpret by researchers/users, shorter training times, to avoid the curse of dimensionality, improve data's compatibility with a learning model class, encode inherent symmetries present in the input space. In practice, feature selection is often used to process high-dimensional data, such as [DNA microarray](https://en.wikipedia.org/wiki/DNA_microarray) data.


## [A brief introduction of feature selection](https://www.zhihu.com/question/19774445/answer/1968792998)
**Schematic representation of the feature selection**
![Schematic representation of the feature selection](https://easy-ai.oss-cn-shanghai.aliyuncs.com/2019-10-31-031529.jpg "Schematic representation of the feature selection")

In general, there are three main types of feature selection methods, namely **filter**, **wrapper** and **embedded**. Some information about these methods can be seen in the figure below.

![feature selection methods](https://github.com/wangxb96/Awesome-Feature-Selection/blob/main/Feature%20selection%20methods.png)


## [Filter Methods](https://github.com/wangxb96/Awesome-Feature-Selection/blob/main/Filter%20Methods.md)
> Filter type methods select variables regardless of the model. They are based only on general features like the correlation with the variable to predict. Filter methods suppress the least interesting variables. The other variables will be part of a classification or a regression model used to classify or to predict data. These methods are particularly effective in computation time and robust to overfitting. Filter methods tend to select redundant variables when they do not consider the relationships between variables. However, more elaborate features try to minimize this problem by removing variables highly correlated to each other, such as the Fast Correlation Based Filter (FCBF) algorithm.
![Filter Methods](https://upload.wikimedia.org/wikipedia/commons/2/2c/Filter_Methode.png)


## [Wrapper Methods](https://github.com/wangxb96/Awesome-Feature-Selection/blob/main/Wrapper%20Methods.md)
> Wrapper methods evaluate subsets of variables which allows, unlike filter approaches, to detect the possible interactions amongst variables. The two main disadvantages of these methods are:
* The increasing overfitting risk when the number of observations is insufficient.
* The significant computation time when the number of variables is large.
![Wrapper Methods](https://upload.wikimedia.org/wikipedia/commons/0/04/Feature_selection_Wrapper_Method.png)


## [Embedded Methods](https://github.com/wangxb96/Awesome-Feature-Selection/blob/main/Embeded%20Methods.md) 
> Embedded methods have been recently proposed that try to combine the advantages of both previous methods. A learning algorithm takes advantage of its own variable selection process and performs feature selection and classification simultaneously, such as the FRMT algorithm.
![Embedded Methods ](https://upload.wikimedia.org/wikipedia/commons/b/bf/Feature_selection_Embedded_Method.png)


## [Graph Based Methods](https://github.com/wangxb96/Awesome-Feature-Selection/blob/main/Graph%20Based%20Methods.md)
![Graph Based Feature Selection](https://www.researchgate.net/profile/Sina-Khanmohammadi/publication/303692787/figure/fig1/AS:367876138651649@1464719914238/Graph-based-feature-selection.png)
