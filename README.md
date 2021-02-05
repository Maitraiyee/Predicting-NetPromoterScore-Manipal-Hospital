# Predicting Net Promoter Score(NPS) to improve Patient experience at Manipal Hospitals

### Objective

The primary objective of the Manipal Hospitals is to improve the overall experience of their patients as “Customer service” was being key to sustaining sales, client loyalty and profits. It is important for every organization to know what their customers tell their friends about the organization.Thus they introduced the concept of “Net Promoter score” which is based on single question: How likely is that you recommend this company or product/service to a friend/colleague? 

The initiative is to collect data in structured manner and translate into meaningful information which could be viewed real time on a Business Intelligence platform. Here the organization is using Analytics to enhance the customer experience and satisfaction.

### Description

The dataset consists of variables representing Patient information like basic info and Demographics and their responses doe each department wise survey for Patient satisfaction. The questionnaire has response levels from 1 to 4 with 1 being Extremely satified and 
4 being Not at all satisfied. Departments include Nursing services, Attendees experience Doctors experience, Admission Process, Customer Engagement etc.

The data has 51 variables with 4989 observations and 1 Target predictor Net promotor score(NPS). NPS is multi- class variable with 3 labels "Promoter", "Detractor", "Passive" depending on the overall satisfaction response the Patient gave in the survey with levels 1 to 10.

Promoter = score > 7

Detractor = score < 6

Passive = 6 < score < 8

This variable can also be treated as binary variable by merging the "Detractor" and "Passive" into a single category "Detractor"

The questionnare variables are converted to Ordinal factors before performing the analysis. I used Anova and Step-wise Logistic regression for Feature selection. I performed RandomForests and Adaboost techniques for predicting the Net promoters. I compared the performance of the techniques on both Binary and Multi class classification problem by using NPS target as both binary and Multi-class variable. The performance of the algorithm on multi-class scenario was way better than that of the binary-class setting.

### Technology

R
