# NASA NEAR EARTH OBJECTS

Dataset -- https://www.kaggle.com/datasets/sameepvani/nasa-nearest-earth-objects

## Predciting the probability whether a space object will collide with Earth or not given the following features

   1. Minimum Estimated Diameter in Kilometres
   2. Maximum Estimated Diameter in Kilometres
   3. Velocity Relative to Earth
   4. Distance in Kilometres missed
   5. Describes intrinsic luminosity
   
## We have used several models for training and making predictions. The most promising models with their metrics looks as follows.
   

###  Random Forest Classifier to predict.- Model [here](https://drive.google.com/file/d/1nUMzuWrM8F_0RGhfb6YpDdk8-tqvIruF/view?usp=sharing)
   1. Accuracy =  0.9202994275649493
   2. F1-Score = 0.4972222222222222
   3. Precision = 0.6580882352941176
   4. ROC-AUC-Score = 0.6884187007118431
   5. Recall = 0.39955357142857145
   
### Voting Classifier with Random Forest and K-Neighbors Classifier. - Model [here](https://drive.google.com/file/d/1UXVTinoJ_JtRZJStEVAOGsRigHcOUKT3/view?usp=sharing) 
   1. Accuracy = 0.9021906649053281
   2. F1-Score = 0.0326619488296135
   3. Precision = 0.6666666666666666
   4. ROC-AUC-Score = 0.5079125484158001
   5. Recall = 0.016741071428571428
   
### Extra Tree Classifier - Model [here](https://drive.google.com/file/d/1n8YluwBep0J1A8hTxQoGY3eU4MIs0yZK/view?usp=sharing)
   1. Accuracy = 0.9172170849845883
   2. F1-Score = 0.5123216601815823
   3. Precision = 0.6114551083591331
   4. ROC-AUC-Score = 0.7050967988868728
   5. Recall = 0.4408482142857143
   
### Voting Classifier with Random Forest and Extra Tree Classifier. - Model [here](https://drive.google.com/file/d/1--GWdIayYDpRfldqhsvwbVS3-MhO1RjK/view?usp=sharing)
   1. Accuracy = 0.9215103478643769
   2. F1-Score = 0.47146034099332834
   3. Precision = 0.7019867549668874
   4. ROC-AUC-Score = 0.6692115857701166
   5. Recall = 0.3549107142857143}
     
   

