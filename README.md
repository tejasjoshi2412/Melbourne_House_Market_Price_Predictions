# Melbourne_House_Market_Price_Predictions

The Dataset has been extracted from Kaggle to predict the house prices in the city of Melbourne,Australia.

Steps for execution:
1. Extracted the Data
2. Perfromed EDA for the different features to check how they ar correlated.
3. Imputed the missing values and dropped features for the missing values which can't be imputed, because a major chunk of missing values were missing from the feature.
4. Performed One Hot Encoding for the categorical features, while keeping in mind the curse of dimensionality.
5. Dropped the irrelevent features which won't be used anymore.
6. Perfromed Feature Scaling using MinMaxScaler.
7. Perfromed a train_train_split for the data to split it into 75% training and 25% testing data. 
8. Created a Machine Learning Model using RandomForestRegressor Algorithm using n_estimators=600.
9. Trained a model and made predictions the accuracy was noted to be 78.56%.
10. Plotted a scatter plot for y_test and predictions they follow an increasing linear relationship.
11. Plotted a residual as well using distplot b calculating y_test-predictions.


Following are the featurs used:

This data was scraped from publicly available results posted every week from Domain.com.au, I've cleaned it as best I can, now it's up to you to make data analysis magic. The dataset includes Address, Type of Real estate, Suburb, Method of Selling, Rooms, Price, Real Estate Agent, Date of Sale and distance from C.B.D.

….Now with extra data including including property size, land size and council area, you may need to change your code!

Some Key Details
Suburb: Suburb

Address: Address

Rooms: Number of rooms

Price: Price in Australian dollars

Method:
S - property sold;
SP - property sold prior;
PI - property passed in;
PN - sold prior not disclosed;
SN - sold not disclosed;
NB - no bid;
VB - vendor bid;
W - withdrawn prior to auction;
SA - sold after auction;
SS - sold after auction price not disclosed.
N/A - price or highest bid not available.

Type:
br - bedroom(s);
h - house,cottage,villa, semi,terrace;
u - unit, duplex;
t - townhouse;
dev site - development site;
o res - other residential.

SellerG: Real Estate Agent

Date: Date sold

Distance: Distance from CBD in Kilometres

Regionname: General Region (West, North West, North, North east …etc)

Propertycount: Number of properties that exist in the suburb.

Bedroom2 : Scraped # of Bedrooms (from different source)

Bathroom: Number of Bathrooms

Car: Number of carspots

Landsize: Land Size in Metres

BuildingArea: Building Size in Metres

YearBuilt: Year the house was built

CouncilArea: Governing council for the area

Lattitude: Self explanitory

Longtitude: Self explanitory
