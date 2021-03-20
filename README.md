# Billboard Rankings Analysis Using Machine Learning Techniques On Spotify

In this study, we propose a machine learning approach to explore how various attributes defined by Spotify for each track affect their ranking positions on Billboard year-end charts and to predict the audience’s music preference. 5 main machine learning techniques were applied under an efficient process that performs concurrent variables and model selection. 
The logistic regression achieved the best results among all of the predictive models. Besides, according to this information, it can be good to analyze target marketing by modeling consumer musical taste.

### Data Source

Billboard will work out a year-end chart based on the ‘Billboard Hot 100’ of each week at the end of each year. The selected charts are from 2010 to 2020, a total of 11 in the count to follow late-year music trend.
Here we will retrieve these annual music charts data from Spotify Web API https://www.spotify.com/us/.

### Methods

We extract 799 observations, account for 90% of the processed dataset, to create the testing set. The rest 10% will be unseen data to test the performance of our predictive models. To avoid overfitting and acquire representative data in each part, the process of splitting the training and test dataset is random. 
The diverse classification algorithms we will use in the project are as follows: Logistic Regression classifier, Random Forest classifier, Decision Tree classifier, K-Nearest Neighbors, Support Vector Machine classifier.


### Results

Performance of the machine learning algorithms used in this project:
| Predictive Model	        | Accuracy Score    | 
| -----------------------   | --------------:   | 
| Logistic Regression       |   26.9663%        |  
| Decision Tree             |   20.2247 %       |  
| Random Forest	            |   24.7191 %       |  
| K-Nearest Neighbors (k-NN)| 	17.9775 %       | 
| Support Vector Machine	  |   19.1011 %       | 
| AdaBoostClassifier	      |   18.0 %          | 
| GradientBoostingClassifier| 	19.1 %          | 
| XGBoostsClassifier	      |   24.7 %          | 

Thus, the logistic regression with simple expressions and interpretable parameters is suitable for the rapid prediction of predicting applications in predicting rankings.

Confusion matrix of logistic regression:

<img src="https://github.com/nilijing/Billboard-Rankings-Analysis-Using-Machine-Learning-Techniques-On-Spotify/blob/main/image/Picture1.png" width="400"  />
