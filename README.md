# Proposal: Analysis_of_Claims_of_Emcien

__Motivation:thought_balloon::__
The motivation of building models to predict auto insurance claim is to help individuals to gain a better
understanding of the factors that contribute to claim amount and how consumers can
potentially get their claim approved. Consumers can identify the variables that are most influential in
determining claim response, such as months since last claim,,	number of open complaints, and policy type.
Having this information can help consumers make informed decisions when selecting insurance policies
or even providers if you have relavent datasets. Furthermore, predictive models can help consumers take steps to lower their
insurance costs. For instance, by analyzing the variables that impact their premiums, consumers
can make changes to their lifestyle or behavior that may reduce their risk of filing a claim.

__Data:mag_right::__
The data we plan to use is mainly from a published dataset. This raw data covers dozens of attributes across geographic
location and demographic information. In order to add background information, we decided to add Consumer
Price Index(CPI), Gross domestic product(GDP), and total traffic fatalities with respect to states and years. Hence,
further manipulation is necessary to get useful insights and statistics. The first step is to modify terms.
For example, since the original data consists lots of object attributes, we need to change it into
categorical ones if we intend to apply Random Forest or Classification And Regression Tree(CART). 
We need to evaluate, process, and clean them first using programming languages or tools
before feeding to our models.

__Model:chart_with_upwards_trend::__
Predicting the cost of insurance is a continuous problem so the analytical methods that
we plan to use may include regression models like linear regression, CART, Random Forest or
Boosting (may include neural networks). Because there are a lot of empty entry values in
columns, and the column numbers are slightly high, we consider to perform PCA to get the
dimensional reduction before running the analysis.
We will test the performance of our model in the test set and use the bootstrap methods to
construct the confidence interval for our model validation.

__Impact:speech_balloon::__
By developing a predictive model for claim amount, consumers can better understand
the factors that impact the claim amount and the response and take measures to determine theie auto
insureance plan, thus improving their economic benefits. Additionally, insurance companies can use our model to
identify which variables most impact claim amount and adjust their insurance products
and prices to more accurately reflect risk. Public policy makers can also use our model to
develop more effective policies to protect consumer interests and promote healthy and safe 
lifestyles. Governments can provide more prevention measures and resources to help people
reduce the risk of accidents, thereby reducing the cost of medical and insurance
expenses.
