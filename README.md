# Loan-Default-Risk-Assessment-Analysis---EDA-
# # Analysis Notes

# Most of the customers have taken cash loan
# Customers who have taken cash loans are less likely to default
# 
# CODE_GENDER - 
# 
#     Most of the loans have been taken by female
#     default rate for females is just ~7% which is safer and lesser than male
# 
# NAME_TYPE_SUITE - 
# 
#     Unacompanied people had taken most of the loans and the default rate is ~8.5% which is still okay
# 
# NAME_INCOME_TYPE - 
# 
#     The safest segments are working, commercial associates and pensioners
# 
# NAME_EDUCATION_TYPE - 
# 
#     Higher education is the safest segment to give the loan with a default rate of less than 5%
# 
# NAME_FAMILY_STATUS - 
# 
#     Married people are safe to target, default rate is 8%
# 
# 
# NAME_HOUSING_TYPE - 
# 
#     People having a house/apartment are safe to give the loan with a default rate of ~8%
# 
# OCCUPATION_TYPE - 
# 
#     Low-skill labourers and drivers are the highest defaulters
#     Accountants are less defaulters
#     Core staff, Managers and Laborers are safer to target with a default rate of <= 7.5 to 10%
# 
# ORGANIZATION_TYPE - 
# 
#     Transport type 3 highest defaulter
#     Others, Business Entity Type 3, Self Employed are good to go with default rate around 10 %
# 
# =======univariate numeric variables analysis========
# 
#     >> Most of the loans were given for the goods price ranging between 0 to 1 ml
#     >> Most of the loans were given for the credit amount of 0 to 1 ml
#     >> Most of the customers are paying annuities of 0 to 50 K
#     >> mostly the customers have income between 0 to 1 ml
# 
# =============bivariate analysis==================
# 
#     >> AMT_CREDIT and AMT_GOODS_PRICE are linearly correlated, if the AMT_CREDIT increases the defaulters are decreasing
#     >> People having income less than or equal to 1 ml, are more like to take loans out of those who are taking loans of less than 1.5 million, and could turn out to be defaulters. we can target income below 1 million and loan amounts greater than 1.5 million
#     >> People having children 1 to less than 5 are safer to give the loan
#     >> People who can pay the annuity of 100K are more like to get the loan and that's up to less than 2ml (safer segment)
# 
# ============analysis on merged data==============
# 
#     >> for the repairing purpose customers had applied mostly prev. and the same purpose has the most number of cancellations
#     >> most of the app. which were prev. either canceled or refused 80-90% of them are repayer in the current data
#     >> offers that were unused prev. now have the maximum number of defaulters despite of having high-income band customers

# # Final Conclusion/Insights

# The bank should target the customers
# 
#     >> Having low income i.e. below 1 ml
#     >> working in Others, Business Entity Type 3, Self Employed  org. type
#     >> Working as Accountants, Core staff, Managers and Laborers 
#     >> Having house/apartment and are married and having children not more than 5
#     >> Highly educated
#     >> preferably female
# 
#     >> Unaccompanied people can be safer -  default rate is ~8.5%
# Amount segment recommended -
# 
#     >> The credit amount should not be more than 1 ml
#     >> Annuity can be made of 50K (depending on the eligibility)
#     >> income bracket could be below 1 ml
# 
#     >> 80-90% of the customers who were prev. cancelled/refused, are repayers. Bank can do the analysis and can consider giving loans to these segments
# 
# 
# ====================precautions===============
# 
#     >> org. Transport type 3 should be avoided
#     >> Low-skill labourers and drivers  should be avoided
#     >> offers prev. unused and high-income customers should be avoided


