PROBAT'S QUALITY EVALUATION & COST BENEFIT ANALYSIS MODEL 📊 

Kaggle dataset link : https://www.kaggle.com/datasets/podsyp/production-quality/data

Algorithms Overview	: 

_Random Forest_ 🌳🌲🌲​
Chosen For: Its robustness, ability to handle large datasets, and reduced risk of overfitting.​

_​AdaBoost_ ⚡🎯​
Chosen For: Its effectiveness in enhancing classification performance.​

_Support Vector Classifier_ (SVC) 🔵🔴​
Chosen For: Its high-dimensional performance and robustness against overfitting.​

_Logistic Regression_ 📈➰​
Chosen For: Its simplicity, interpretability, and effectiveness for binary classification tasks.​

_Significant Predictors:_

Key Features Influencing Product Quality:​

​Temperature (Chamber 1, 2, 3): Higher temperatures lead to improved quality.​

Humidity: Lower humidity levels correlate with higher quality scores.​

Raw Material Layer Height: Optimal height ensures even cooking, impacting quality positively.​

Based on feature importance in the Random Forest model, temperature readings, raw material layer height, and humidity emerged as key factors impacting product quality. These insights indicate that small variations in temperature, material thickness, and humidity may strongly correlate with quality outcomes.​

_Cost-Benefit Analysis:_

How We Calculate Costs with the RF Model
We use the Random Forest model’s predictions to calculate total costs based on its classification errors. Here’s the breakdown:

Total False Positive Cost: The model made 212 false positives, costing:

212
×
€
5
,
000
=
€
1
,
060
,
000
212×€5,000=€1,060,000
Total False Negative Cost: The model made 258 false negatives, costing:

258
×
€
500
=
€
129
,
000
258×€500=€129,000


Total Cost of RF Model Misclassifications:


€1,060,000+€129,000=€1,189,000

Comparing Costs: RF Model vs. Manual Inspection
If we inspect each product manually, the total inspection cost (including misclassifications) would be €4,852,174.50.

Using the RF model instead of manual checks saves us a lot of money:

Manual Inspection Cost: €4,852,174.50
RF Model Cost: €1,189,000
Cost Savings:
€
4
,
852
,
174.50
−
€
1
,
189
,
000
=


€4,852,174.50−€1,189,000=€3,663,174.50


Cost Estimates:​

Random Forest: €1,189,000​

AdaBoost: €1,445,000​

SVC: €1,458,000​

Logistic Regression: €1,627,500​

Recommendation: Implementation of Random Forest as it offers the best performance, cost-effectiveness, and minimizes risks associated with low-quality products. The model minimizes costly errors (false negatives and false positives), thereby protecting the brand's premium image and reducing the risk of subpar products reaching the market.​

​
