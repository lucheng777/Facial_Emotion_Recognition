# Project 3: Predictive Modeling - Image Analysis
<img src="figs/CE.jpg" alt="Compound Emotions" width="500"/>
(Image source: https://www.pnas.org/content/111/15/E1454)

### [Full Project Description](doc/Main.ipynb)

Term: Spring 2020

+ Team ##
+ Team members
	+ David Heagy
	+ Hanbo Jiao 
	+ Lu Cheng  
	+ Marsya Chairuna 
	+ Zhongtian Pan 

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
	
+ **Contribution statement:** All team members contributed in all stages of this project. 
  
  + **David Heagy** carried out the trainings using (1) KNN and (8) MLP Classifier. David Heagy actively took part and shared his thoughts during our weekly group discussion. 
  
  + **Hanbo Jiao** took the lead in extracting features from the dataset and training the majority of the models, using (2) GBM/Improved GBM, (3) XGBoost, (5) Logistics Regression, (7) Support Vector Machine. Hanbo Jiao also took the first cut on creating our Main Jupyter notebook, summarizing all the performance of candidate models, and finalizing it. Hanbo Jiao also ran the trainings for the final VotingClassifier to combine the top-performing models. Hanbo Jiao actively took part and shared his thoughts during our weekly group discussion. 
  
  + **Lu Cheng** carried out the training using (4) Random Forest Classifier. Lu Cheng is the presenter for this project. 
  
  + **Marsya Chairuna** carried out the training using (6) Logistics Regression with PCA. Marsya Chairuna worked on, edited and organized the README file and the Main Jupyter notebook. Marsya Chairuna actively took part and shared his thoughts during our weekly group discussion. 

  + **Zhongtian Pan** carried out parameters tuning for all the candidates and final models. 
  
All team members approve our work presented in this GitHub repository including this contributions statement.

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
