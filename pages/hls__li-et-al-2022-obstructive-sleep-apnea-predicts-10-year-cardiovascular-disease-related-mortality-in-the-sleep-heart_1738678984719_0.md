file:: [li-et-al-2022-obstructive-sleep-apnea-predicts-10-year-cardiovascular-disease-related-mortality-in-the-sleep-heart_1738678984719_0.pdf](../assets/li-et-al-2022-obstructive-sleep-apnea-predicts-10-year-cardiovascular-disease-related-mortality-in-the-sleep-heart_1738678984719_0.pdf)
file-path:: ../assets/li-et-al-2022-obstructive-sleep-apnea-predicts-10-year-cardiovascular-disease-related-mortality-in-the-sleep-heart_1738678984719_0.pdf

- The commonly used evaluation tools of 10-year CVD risk(eg, Framingham Risk Score7 ), however, do not include sleep factors as predictors
  ls-type:: annotation
  hl-page:: 1
  hl-color:: yellow
  id:: 67a334f9-4931-4d6c-b3b1-a67be810bc15
- provide personalized prediction
  ls-type:: annotation
  hl-page:: 1
  hl-color:: yellow
  id:: 67a33518-d4d7-4f82-8ccc-47888d3f3f39
- ses mutual information
  ls-type:: annotation
  hl-page:: 1
  hl-color:: red
  id:: 67a33523-9a16-4175-be0d-8cb36875c69e
- random forest modeling
  ls-type:: annotation
  hl-page:: 1
  hl-color:: red
  id:: 67a33529-5f7e-41e5-8890-74fb576fa1ab
- Sleep was scored according to criteria described by Rechtschaffen and Kales.
  ls-type:: annotation
  hl-page:: 2
  hl-color:: yellow
  id:: 67a335be-147f-44c6-ae3a-e72b51c4fea9
- Selection of features to be used in model development was based on previous studies documenting their association with CVD
  ls-type:: annotation
  hl-page:: 2
  hl-color:: yellow
  id:: 67a3361a-3619-4003-8c8e-bc7ad4b147fb
- We randomly separated the 2,464 participants into 2 sets: a training set (n = 1971) and a test set (n = 493)
  ls-type:: annotation
  hl-page:: 3
  hl-color:: yellow
  id:: 67a33669-c163-42f1-a10b-c09a0874eb9f
- ensemble learning algorithm
  ls-type:: annotation
  hl-page:: 3
  hl-color:: red
  id:: 67a336a0-8bbb-4620-8417-b9f9d0353580
- weighted averaging method to improve their predictive accuracy
  ls-type:: annotation
  hl-page:: 3
  hl-color:: red
  id:: 67a336ac-6705-46b1-a31d-75f51d0fe7ea
- mutual information technology with 5-fold stratified cross validation to evaluate the importance of the features
  ls-type:: annotation
  hl-page:: 4
  hl-color:: red
  id:: 67a33723-d24f-4250-8491-bc3e38bc139a
- The top 50% of features (9 features) with the highest mutual information were selected as input to train the random forest model
  ls-type:: annotation
  hl-page:: 4
  hl-color:: red
  id:: 67a3379b-7830-44b7-84ff-e7c71caa8f15
- The random forest model was implemented by Python package Scikit-learn v0.23
  ls-type:: annotation
  hl-page:: 4
  hl-color:: red
  id:: 67a337b2-5968-4210-8533-fab08c4a52e2
- Grid search with stratified 5-fold cross validation was used to find the optimal values of hyperparameters
  ls-type:: annotation
  hl-page:: 4
  hl-color:: red
  id:: 67a337c2-a1b2-4fd7-a158-e7142fcf3c77
- We used the area under the receiver operating curve (AUC) as the metric to evaluate performance
  ls-type:: annotation
  hl-page:: 4
  hl-color:: yellow
  id:: 67a337e5-e791-4fef-9c3f-ac396f797d08
- emographic, anthropometric and clinical characteristics of datasets. We did not find statistically significant differences between the training set and test set.
  ls-type:: annotation
  hl-page:: 4
  hl-color:: green
  id:: 67a338d3-17f9-48ae-b7ac-61a9dca5b0ad
- The age feature had the highest mutual information
  ls-type:: annotation
  hl-page:: 4
  hl-color:: green
  id:: 67a338f7-c6c3-4f29-8244-ce36d05ea780
- FVC and FEV1 have higher mutual information
  ls-type:: annotation
  hl-page:: 4
  hl-color:: green
  id:: 67a33903-5b95-4c97-8065-f18239342435
- the dependency between10-year CVD mortality and AHI was lower than for FEV 1 and FVC but higher than for diabetes, high density lipoprotein, body mass index, and cholesterol.
  ls-type:: annotation
  hl-page:: 5
  hl-color:: green
  id:: 67a33919-7340-4602-8a46-f71ab3724d11
- As age and AHI increase, the probability of CVD mortality after 10 years increases as well
  ls-type:: annotation
  hl-page:: 5
  hl-color:: green
  id:: 67a3396f-815e-4bf4-96af-1da331053e92
- persons with severe OSA (AHI = 35 events/h) have a1.057-fold (95% confidence interval: 1.055–1.059) greater risk than those with mild OSA (AHI = 5 events/h).
  ls-type:: annotation
  hl-page:: 5
  hl-color:: green
  id:: 67a33997-b3ef-48ac-9804-d751a848c2ed
- Our finding that the random forest model performed better than use of the Framingham Risk Score is of particular interest.
  ls-type:: annotation
  hl-page:: 6
  hl-color:: green
  id:: 67a339d2-baf7-4d11-a2ae-327b7a0403ca
- In contrast, the most important features in our approach had little overlap with the Framingham Risk Score with the exception of age and history of hypertension. Thus, it appears that in an OSA population, factors predicting 10-year CVD mortality are different than in a general adult population.
  ls-type:: annotation
  hl-page:: 7
  hl-color:: green
  id:: 67a339f4-8bf0-44a5-8cfd-843c3acc12a0
- Interestingly, we found that pulmonary function (FEV 1 and FVC) was an important predictor of mortality.
  ls-type:: annotation
  hl-page:: 7
  hl-color:: green
  id:: 67a33a5e-b01e-49c5-9d42-5a60680fd6be
- A bootstrap method
  ls-type:: annotation
  hl-page:: 4
  hl-color:: red
  id:: 67a5d0e8-d67a-47bf-a42a-2df97e4d97e2