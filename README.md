# kc_house_data
# Description :
Online property companies offer valuations of houses using machine learning techniques. The dataset consisted of historic data on houses sold between Jun 2014 to Dec 2015.
The dataset consists of house prices from King County an area in the US State of Washington, this data also covers Seattle. The dataset was obtained from Kaggle. This data was published/released under CC0: Public Domain. Unfortunately, the user has not indicated the source of the data. Please find the citation and database description in the Glossary and Bibliography. The dataset consisted of 21 variables and 21613 observations.

# Columns :
* id : A property identification number is a number assigned to parcels of real property by the tax assessor of a particular jurisdiction for purposes of identification and record keeping.
* date : Date of transaction
* price : Price of house
* bedrooms, bathrooms : Number
* sqft_living, sqft_lot : The Original square footage of the living and lot space when the house was built
* floors : Total floors in the house
* waterfront: Whether the house is on a waterfront(1: yes, 0: no)
* view : special view?
* condition : Condition of the house
* grade : Simply put, the grade or grading around your house is the level of the ground. The ground level and how it's graded is the deciding factor of where storm water will flow
* sqft_above,sqft_basement : Square footage of house apart from basement and basement area
* yr_built : Built year
* yr_renovated : Year when the house was renovated
* zipcode, lat, long : zip code, latitude and logtitude coordinate of the house
* sqft_living15, sqft_lot15 : The latest square footage of the living and lot space ( was taken in 2015 )

# 1. Data Showing, Understanding, and Manipulation :
## 1.1 what did we have?
## 1.2 There are Missing or Duplicated data?
## 1.3 Which columns are not useful?
## 1.3 Data integration
## 1.4 Manipulate Columns Wrong Formating
## 1.4.1 Modify Memory Usage
## 1.4.2 Zeros
# 2.Data Analysis
## 2.1 Outliers
* Function that handle outliers
* it takes 5 parameters
* df = DataFrame that we work on it
* Display = if u wanna see a box plot of all numerical columns " default = False "
* Drop = if u wanna drop Outliers " default = False "
* drop_order = we know that when we drop outliers, the distribution of data will change, that's mean it's possible to appear outliers again in the same column!     drop_order handling this " default = 1 ", drop for one time
* columns_to_drop = if u wanna drop specific columns

## 2.2 Min, Mean,Max , and change in mean House Price for each city
## 2.3 Categorise Price
## 2.3.1 How Average price change for each category of prices over two years
## 2.3.2 Average transaction price per month over two years
## 2.3.3 Total transactions price each month
## 2.4 Average price per Sqft
## 2.4.1 Average price per Sqft each city
## 2.5 Decision Making
* if i own a home and i wanna sell it by good price, but i'll renovate it first which's better ? maximize living area or lot area !!
## 2.6 House Age
## 2.6.1 The number of houses built each year
## 2.6.2 Most homes that have been modified in all year
## 2.6.3 House Age vs Average price
## 2.7 transactions happen in each year and month over two years
## 2.8 How basement Affect on price?
## 2.9 Grade, bed , bath , floors ,condition , Vs Average Price
## 2.9.1 Grade
## 2.9.2 Bedrooms
## 2.9.3 Bathrooms
* What does 2.5 bathrooms mean? In the US it means there are two "full bathrooms" and one “half” bathroom.
* A full bathroom has a sink, toilet, half bathroom has a tub/shower combo or separate tub and shower.
## 2.9.4 Floors
## 2.9.5 Condition of house
## 2.10 Population & Population denisty
## 2.10.1 Population for each city
## 2.10.2 Population Vs Price via Date
## 3. Average Price Vs all features
## 4. Future work!
* The percentage increase or decrease in the average price with the change of each percentage of the features.
