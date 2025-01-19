SK_ID_CURR: ID of loan in our sample - one loan in our sample can have 0,1,2 or more related previous credits in credit bureau -- hashed
SK_ID_BUREAU: Recoded ID of previous Credit Bureau credit related to our loan (unique coding for each loan application) -- hashed
CREDIT_ACTIVE: Status of the Credit Bureau (CB) reported credits - CATEGORICAL
CREDIT_CURRENCY: Recoded currency of the Credit Bureau credit -- recoded - CATEGORICAL
DAYS_CREDIT: How many days before current application did client apply for Credit Bureau credit -- time only relative to the application
CREDIT_DAY_OVERDUE: Number of days past due on CB credit at the time of application for related loan in our sample
DAYS_CREDIT_ENDDATE: Remaining duration of CB credit (in days) at the time of application in Home Credit -- time only relative to the application
DAYS_ENDDATE_FACT: Days since CB credit ended at the time of application in Home Credit (only for closed credit) -- time only relative to the application
AMT_CREDIT_MAX_OVERDUE: Maximal amount overdue on the Credit Bureau credit so far (at application date of loan in our sample)
CNT_CREDIT_PROLONG: How many times was the Credit Bureau credit prolonged
AMT_CREDIT_SUM: Current credit amount for the Credit Bureau credit
AMT_CREDIT_SUM_DEBT: Current debt on Credit Bureau credit
AMT_CREDIT_SUM_LIMIT: Current credit limit of credit card reported in Credit Bureau
AMT_CREDIT_SUM_OVERDUE: Current amount overdue on Credit Bureau credit
CREDIT_TYPE: Type of Credit Bureau credit (Car, cash,...) - CATEGORICAL
DAYS_CREDIT_UPDATE: How many days before loan application did last information about the Credit Bureau credit come -- time only relative to the application
AMT_ANNUITY: Annuity of the Credit Bureau credit