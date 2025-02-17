SK_ID_PREV: ID of previous credit in Home credit related to loan in our sample. (One loan in our sample can have 0,1,2 or more previous loan applications in Home Credit, previous application could, but not necessarily have to lead to credit) -- hashed

SK_ID_CURR: ID of loan in our sample -- hashed

NAME_CONTRACT_TYPE: Contract product type (Cash loan, consumer loan [POS] ,...) of the previous application

AMT_ANNUITY: Annuity of previous application

AMT_APPLICATION: For how much credit did client ask on the previous application

AMT_CREDIT: Final credit amount on the previous application. This differs from AMT_APPLICATION in a way that the AMT_APPLICATION is the amount for which the client initially applied for, but during our approval process he could have received different amount - AMT_CREDIT

AMT_DOWN_PAYMENT: Down payment on the previous application

AMT_GOODS_PRICE: Goods price of good that client asked for (if applicable) on the previous application

WEEKDAY_APPR_PROCESS_START: On which day of the week did the client apply for previous application

HOUR_APPR_PROCESS_START: Approximately at what day hour did the client apply for the previous application -- rounded

FLAG_LAST_APPL_PER_CONTRACT: Flag if it was last application for the previous contract. Sometimes by mistake of client or our clerk there could be more applications for one single contract

NFLAG_LAST_APPL_IN_DAY: Flag if the application was the last application per day of the client. Sometimes clients apply for more applications a day. Rarely it could also be error in our system that one application is in the database twice

RATE_DOWN_PAYMENT: Down payment rate normalized on previous credit -- normalized

RATE_INTEREST_PRIMARY: Interest rate normalized on previous credit -- normalized

RATE_INTEREST_PRIVILEGED: Interest rate normalized on previous credit -- normalized

NAME_CASH_LOAN_PURPOSE: Purpose of the cash loan

NAME_CONTRACT_STATUS: Contract status (approved, cancelled, ...) of previous application

DAYS_DECISION: Relative to current application when was the decision about previous application made time only relative to the application

NAME_PAYMENT_TYPE: Payment method that client chose to pay for the previous application

CODE_REJECT_REASON: Why was the previous application rejected

NAME_TYPE_SUITE: Who accompanied client when applying for the previous application

NAME_CLIENT_TYPE: Was the client old or new client when applying for the previous application

NAME_GOODS_CATEGORY: What kind of goods did the client apply for in the previous application

NAME_PORTFOLIO: Was the previous application for CASH, POS, CAR, Ö

NAME_PRODUCT_TYPE: Was the previous application x-sell o walk-in

CHANNEL_TYPE: Through which channel we acquired the client on the previous application

SELLERPLACE_AREA: Selling area of seller place of the previous application

NAME_SELLER_INDUSTRY: The industry of the seller

CNT_PAYMENT: Term of previous credit at application of the previous application

NAME_YIELD_GROUP: Grouped interest rate into small medium and high of the previous application -- grouped

PRODUCT_COMBINATION: Detailed product combination of the previous application

DAYS_FIRST_DRAWING: Relative to application date of current application when was the first disbursement of the previous application -- time only relative to the application

DAYS_FIRST_DUE: Relative to application date of current application when was the first due supposed to be of the previous application -- time only relative to the application

DAYS_LAST_DUE_1ST_VERSION: Relative to application date of current application when was the first due of the previous application -- time only relative to the application

DAYS_LAST_DUE: Relative to application date of current application when was the last due date of the previous application -- time only relative to the application

DAYS_TERMINATION: Relative to application date of current application when was the expected termination of the previous application -- time only relative to the application

NFLAG_INSURED_ON_APPROVAL: Did the client requested insurance during the previous application