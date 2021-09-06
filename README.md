# KC Housesales Data


Online property companies offer valuations of houses using machine learning techniques. The aim of this report is to predict the house sales in King County, Washington State, USA using Multiple Linear Regression (MLR). The dataset consisted of historic data of houses sold between May 2014 to May 2015.

### Problem Statement
“Predict the sales of houses in King County with an accuracy of at least 75-80% and understand which factors are responsible for higher property value - $650K and above.”

### Database Description
The dataset consists of house prices from King County an area in the US State of Washington, this data also covers Seattle. The dataset was obtained from Kaggle. This data was published/released under CC0: Public Domain. Unfortunately, the user has not indicated the source of the data. Please find the citation and database description in the Glossary and Bibliography.

The dataset consisted of 21 variables and 21613 observations.
Due to the “Grade” variable which is based on a grading system specific to King County, it seems likely that the data originated from an official source. On the other hand, the existence of the “View” variable relates to the number of viewings the property received. This suggests that the data originated from a real estate agent/company.

In either case, there is no reason to call into question the general accuracy of the data because values such as prices, area etc. do not appear random. Nevertheless, some caution is appropriate before applying models trained on this data to more general cases.

### Variables Description Data Type
id a notation for a house Numeric
date Date house was sold String
price Price is prediction target Numeric
bedrooms Number of Bedrooms/House Numeric
bathrooms Number of bathrooms/bedrooms Numeric
sqftliving square footage of the home Numeric sqftlot square footage of the lot Numeric
floors Total floors (levels) in house Numeric
waterfront House which has a view to a waterfront Numeric
view Has been viewed Numeric
condition How good the condition is ( Overall ). 1 indicates worn out property and 5 excellent.(http://info.kingcounty.gov/assessor/esales/Glossary.aspx?type=r#g) Numeric
grade overall grade given to the housing unit, based on King County grading system. 1 poor ,13 excellent. Numeric
sqftabove square footage of house apart from basement Numeric sqftbasement square footage of the basement Numeric
yrbuilt Built Year Numeric yrrenovated Year when house was renovated Numeric
zipcode zip Numeric
lat Latitude coordinate Numeric
long Longitude coordinate Numeric
sqftliving15 Living room area in 2015(implies-- some renovations) This might or might not have affected the lotsize area Numeric sqftlot15 lotSize area in 2015(implies-- some renovations) Numeric
