# Credit_Risk_Analysis


## Overview of the analysis: Explain the purpose of this analysis.
The purpose of the analysis was to train a machine learning model to determine credit card risk based on a number of factors. Different techniques were used, such as RandomOverSampler, SMOTE, ClusterCentroids, SMOTEENN, BalancedRandomForestClassifier, and EasyEnsembleClassifier. These were needed because good loans greatly outnumber risky loans.



## Results: Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all six machine learning models. Use screenshots of your outputs to support your results.


- RandomOverSampler
  - The accuracy score was only about 65%. The precision for low risk was perfect (overfitting), but precision for high risk was only at 1%. The recall score for high risk was 71%, while the recall score for low risk was only 58%.
  - ![image](https://user-images.githubusercontent.com/40220871/161472511-483f84ea-5a50-49ed-9329-6413f539d53e.png)


- SMOTE
  - The accuracy score was also only about 65%. The precision for low risk was perfect (overfitting), but precision for high risk was only at 1%. The recall score for high risk was 63%, while the recall score for low risk was 66%.
  - ![image](https://user-images.githubusercontent.com/40220871/161472526-b2a14a90-bc5a-4812-a345-ef7f13b73bd1.png)


- ClusterCentroids
  - The accuracy score was also only about 65%. The precision for low risk was perfect (overfitting), but precision for high risk was only at 1%. The recall score for high risk was 68%, while the recall score for low risk was only 52%.
  - ![image](https://user-images.githubusercontent.com/40220871/161472542-7cb6a20b-c3ea-481d-81cf-eccd0a450320.png)


- SMOTEENN
  - The accuracy score was only about 60% (worse than the others). The precision for low risk was still perfect (overfitting), but precision for high risk was only at 1%. The recall score for high risk was 70%, while the recall score for low risk was 60%.
  - ![image](https://user-images.githubusercontent.com/40220871/161472556-3a85afd2-83bf-4b71-961e-34c891e626d0.png)


- BalancedRandomForestClassifier
   - The accuracy score was only 50%. The precision for low risk was 0%, but precision for high risk was perfect (overfitting). The recall score for high risk was perfect (overfitting), while the recall score for low risk was 0%.
   - ![image](https://user-images.githubusercontent.com/40220871/161472723-e2c875df-00a0-458b-8d89-4de416f8f181.png)
   


- EasyEnsembleClassifier
   - The accuracy score was only about 61%. The precision for low risk was perfect (overfitting), but precision for high risk was only at 1%. The recall score for high risk was 56%, while the recall score for low risk was only 66%.
   - ![image](https://user-images.githubusercontent.com/40220871/161472748-d5376279-83b5-4b33-b095-6dfa94f10247.png)



Summary: Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. If you do not recommend any of the models, justify your reasoning.
