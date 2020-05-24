# Predictive Modeling - Image Analysis
<img src="figs/CE.jpg" alt="Compound Emotions" width="500"/>
(Image source: https://www.pnas.org/content/111/15/E1454)

### [Full Project Description](doc/Main.ipynb)

+ Project summary: In this project, we created a classification engine for facial emotion recognition. We trained and compared seven prediction models below. For all the candidate models, we observe the claimed accuracy, training time, and testing time. We will select the best-performing model based on these three performance parameters.

  + (1) KNN (Claimed accuracy: **30.36%**)
  + (2) GBM/Improved GBM (**41.92%**/**43.32%**)
  + (3) XGBoost (**47.12%**)
  + (4) Random Forest Classifier (**45.48%**)
  + (5) Logistics Regression (**54.00%**)
  + (6) Logistics Regression with PCA (**55.20%**)
  + (7) Support Vector Machine (**50.04%**)
  + (8) MLP Classifier (**49.44%**)

Finally, we used VotingClassifier to combine the top-performing models together as the finals model, which achieve the testing accuracy of **53%**. 
	

Following [suggestions](http://nicercode.github.io/blog/2013-04-05-projects/) by [RICH FITZJOHN](http://nicercode.github.io/about/#Team) (@richfitz). This folder is orgarnized as follows.

```
proj/
├── lib/
├── data/
├── doc/
├── figs/
└── output/
```

Please see each subfolder for a README file.
