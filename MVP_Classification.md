#  Tawakkalna Application

The goal of this project is to find reviews that have problems in application and fix it.





To reach this goal, we investigated the data that i scripted from apple store and google play form Tawakkalna Application for reviews of Application, and through this data and after analyzing it, i found reviews which was imbalance as shown in figuer below ,and data after balanced.

![](MVP_image/imbalance_data.png) ![](MVP_image/balanced_data.png)   


After that i got frequency for every word and i got more than 5600 word and frequency for every word. 

And through this data i'm able to predict the sentiment for reviews and knows reviews that have problems in application, and the best model i reach it was (Random Forest Classifier):

Accuracy Train = 0.93922,
Accuracy validation = 0.84165,
Accuracy Test = 0.83566
-------------------------
F1 Train = 0.93667,
F1 validation = 0.83048,
F1 Test = 0.83132
-------------------------
Recall Train = 0.90139,
Recall validation = 0.78677,
Recall Test = 0.79253
-------------------------
Precision Train = 0.97482,
Precision validation = 0.87934,
Precision Test = 0.87410
-------------------------
F2 Train = 0.91518,
F2 validation = 0.80369,
F2 Test = 0.80761
-------------------------


![](MVP_image/confusion_matrix.png)  
![](MVP_image/roc_auc_score.png) 


