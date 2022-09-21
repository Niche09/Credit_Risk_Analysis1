# Cryptocurrencies

Results
-----------

RandomOverSampler
-------
*The RandomOverSampler model resulted in classifying 51,366 records each as high risk and low risk.

<img width="311" alt="image" src="https://user-images.githubusercontent.com/106127571/191397739-1c27e1a2-81fa-4ea7-9156-f4568528b211.png">

*Balanced accuracy score: 65%

<img width="307" alt="image" src="https://user-images.githubusercontent.com/106127571/191397959-d0018fae-cc98-4904-8c4e-1b4d92dbbf0f.png">



*The high risk precision rate is 1% with recall at 71%.
*The low risk precision rate is 100% and recall at 60%.

<img width="520" alt="image" src="https://user-images.githubusercontent.com/106127571/191398477-2442fde1-6141-469a-807e-6d53175133f7.png">

SMOTE Oversampling
-----

* The balanced accuracy score improved slightly to 66%.

<img width="283" alt="image" src="https://user-images.githubusercontent.com/106127571/191398722-d62f5e1a-38a7-4b1a-a579-0b761ba4486c.png">

* The high risk precision rate is again 1% with the recall of 63%.
* The low rish precision rate is 100% and recall of 69%.


<img width="536" alt="image" src="https://user-images.githubusercontent.com/106127571/191399183-48e26f4e-100b-40a7-b582-8a9db126ea6e.png">


UnderSampling
----
* The ClusterCentroids Model classified 246 records as high risk and low risk.

<img width="337" alt="image" src="https://user-images.githubusercontent.com/106127571/191399946-721b81d3-e52e-4f1a-b73f-4c0620a605c8.png">


* The balanced accuracy score is 54% which is lower than the oversampling models.

<img width="272" alt="image" src="https://user-images.githubusercontent.com/106127571/191400652-d5770274-4e6c-4561-95e0-5c4114dfe5d6.png">


* The high risk precision rate is 1% and the recall is 69%.
* The low risk precision rate is 100% and recall is 40%.

<img width="508" alt="image" src="https://user-images.githubusercontent.com/106127571/191400916-8ae8ace0-8c6c-4d11-9030-243cfe65a1ac.png">


Combination (Oversampling)
-------

* SMOTEEN uses both undersampling and oversampling and the model classified 68,460 records as high risk and 62,011 records as low risk.

<img width="340" alt="image" src="https://user-images.githubusercontent.com/106127571/191401525-38e984d5-cd53-44a8-96c3-5b7492b7044f.png">


* The balance accuracy is better at 64%.
<img width="207" alt="image" src="https://user-images.githubusercontent.com/106127571/191402092-5ade535c-8519-453f-9f07-19f7bc0e2daf.png">


* The high risk precision rate is 1% and the recall is better at  72%.
* The low risk precision rate is 100% and recall is 57%.



<img width="558" alt="image" src="https://user-images.githubusercontent.com/106127571/191402821-0e78b942-2b70-4c98-bb37-ea525b2035e7.png">


Ensemble Classifiers
-----
<img width="314" alt="image" src="https://user-images.githubusercontent.com/106127571/191404546-bc2a87c4-56b8-4e7c-b2fb-4e0790157c85.png">

* The models classified 51,366 records as high risk and 246 records a low risk.


BalancedRandomForestClassifier Model
-------

* The balanced accuracy score inresaed to 79% for this model.
* The high risk precision rate increased to 3% with the recall at 70%.
* Low risk has a precision rate of 100% with the recall at 89%.


Summary
-------

The EasyEnsembleClassifier model had the best results with accuracy rate of 93% and 9% prescion rate when predicting high risk candidates. The results for predicting was highest at 94%. This is the best model for this type of analysis.

EasyEnsembleClassifier Model
---------

* The balanced accuracy score is 93% with this model.
* The high risk precision rate increased to 9% with the recall at 92%.
* Low risk has precision rate at 100% with the recall at 94%.
