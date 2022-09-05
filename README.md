# (Dataset Exploration Title)
## by (your name here)


## Dataset

> The dataset used in this project is popularly known as "Loan Data from Prosper". This data consists of 113,937 loan records of individuals. There are 81 features describing the loan data. The features I considered most important are extracted for this project. These include term, loan status, borrower APR, borrower rate, prosper rating (numeric), prosper score, occupation, income range, loan original amount and recommendations. 



## Summary of Findings

> In this project, the following findings were evident:

•	The distribution of the Borrowers APR data is multimodal as it contains different peaks. The highest peak lies between 0.35 and 0.36. This suggests that the APR of most of the data is between 35-36%.

•	The income of most of the borrowers ranged between 25,000-49,999 followed by 50,000-74,999.

•	The exploration shows that most of the loans were made for 36 months and the prosper ratings of the borrowers follows a normal distribution.

•	Based on correlation analysis, APR is strongly correlated with InterestRate (r = 0.993). Moreover, APR is negatively correlated with LoanAmount (r= -0.428). This is intuitively okay since huge amount of loan should attract lesser APR.

•	The analysis shows that APR is negatively correlated with prosper rating, prosper score, and recommendations. These observations make sense since APR of borrowers that have low risk (i.e., high rating and score) are expected to be low. The same judgement is applicable to recommendations.

•	The exploration shows that APR reduces with term. This means loan with longer term will attract lesser APR. It is also noticed that the loan amount increases with income range. This is reasonable as people with higher income rate should have low risk, hence, they should be able to pay back the loan easily. This observation is confirmed by the relationship between prosper score, prosper rating and income range : the more the income the more the prosper score and prosper rating. However, there is a surprising relationship between prosper rating, prosper score and term. Prosper score increases with term, while prosper rating reduces with term. This is surprising as prosper rating and prosper score measures almost the same thing : risk level of borrowers.

•	The visualization result depicts that current and completed loans have lower APR (mean) compared to those of past due loans. This typifies that people that do not pay up their loans at the right time may get their APR increased.

•	It was discovered that APR reduces with better ratings while loan amount increases with better ratings. For example, the loan amount at APR 0.2 for 6 and 7 prosper rating are about 2300 and 1500, respectively. However, it was noticed the relationship between loan amount and APR changes from negative to slightly positive at the best ratings (i.e., 6 and 7). This may be because people with these best ratings are super rich and the company wants to maximize their profit by increasing their APR since they (borrowers) would not mind paying them.
•	The analysis identifies that past due loans have higher APR mean compared to others. It also shows that the APR increases from term 12 to term 36 and then decrease at term 60 for all the loan status except "defaulted", which its APR decreases from 12 to 60.

•	The result shows that people that are not employed have the highest APR. This is because the loan company considers them to have the highest risk of paying back the loan. Furthermore, it was observed that the APR reduces for each term as the income range increases. This maybe because people with high income range tend to have low risk of paying up. Hence, they have low APR.


## Key Insights for Presentation

>For the presentation purpose, I focus on the most interesting insights found during the exploration analysis of the dataset. These insights revolve around the relationship between APR (the main variable of interest) and loan amount, prosper rating, prosper score, recommendations and income range. I ensure all the visualization plots are polished by including their titiles and appropriate labels. 




