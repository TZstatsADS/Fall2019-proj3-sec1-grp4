# Project: Can you recognize the emotion from an image of a face? 
<img src="figs/CE.jpg" alt="Compound Emotions" width="500"/>
(Image source: https://www.pnas.org/content/111/15/E1454)

### [Full Project Description](doc/project3_desc.md)

Term: Fall 2019

+ Team Section1 Group4
+ Team members
	+ Chen Haofeng (hc2962)
	+ Song Mingming (ms5710)
	+ Yang Yifan (yy2955)
	+ Zhang Shijie (sz2781)
	+ Zhou Zihan (zz2573)

+ Project summary: In this project, we evaluated performances of several different classification methods and selected an optimal classification engine for facial emotion recognition. 
	

**Contribution statement**: ([default](doc/a_note_on_contributions.md)) All team members approve our work presented in this GitHub repository including this contributions statement. 

* Zihan:
  * Implemented baseline model using GBM(Gradient Boosting Machine)
  * Tuned parameters to improve its accuracy. 
* Mingming:
  * In charge of the KNN(K-Nearest Neighbors model) and Decision Tree model
  * Worked on parameter tuning to get better accuracy for both models. 
* Shijie:
  * Implemented the KNN model and the baseline model using XGBoost
  * Conducted parameter tuning to improve the accuracy. 
* Haofeng:
  * Implemented and tuned SVC(Support Vector Classifier) and Random Forest
  * Made slides for the presentation. 
  * Presented our groupwork
* Yifan:
  * Tested all possible models( KNN, Decision Tree, Random Forest, Logistic Regression, Linear SVC, Other SVC, Feedforward Neural Network and Convolutional Neural Network) with three different input feature matrixs (Point coordinates, Point distances and raw images)
  * Edited and summarized groupwork

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
