# ✨CAPSTONE 2 SUPERMARKET CUSTOMER DATASET✨
  HANDIKA EKI WINATA - JCDS 0306 PURWADHIKA

# TITLE OF ANALYSIS: MARKET STRATEGY FORMULATION BY ANALYSING CUSTOMER SHOPPING BEHAVIOR

## **TABLE OF CONTENTS**

1. CASE STUDY
2. DATA UNDERSTANDING
3. PROBLEM STATEMENT
4. DATA CLEANING
5. DATA PREPARATION
6. OUTLIERS HANDLING
7. ANALYSIS AND VISUALIZATION
8. CONCLUSION AND RECOMMENDATION

## **1. CASE STUDY**

DATA SCIENTIST: `HANDIKA EKI WINATA`

STAKEHOLDERS: `STORE MANAGER & MARKETING TEAM OF SUPERMARKET`

SUPERMARKET NAME: `JUST ONE SUPERMARKET`

LOCATION: `BOSTON, USA`

YEAR OF ANALYSIS: `2015`

##  **2. DATA UNDERSTANDING**

Understanding client behavior is critical in the modern retail landscape for organizations to properly customize their offers and marketing campaigns. This dataset provides a comprehensive perspective of supermarket customer attributes, purchasing behavior, and promotional campaign engagement. The dataset consist of customer data points, each of which represents a unique consumer's interaction with the supermarket. It includes a wide range of characteristics, such as demographic information, shopping patterns, response to marketing campaigns, and so on. This dataset was collected near the end of 2014 and describes customer purchases within the previous two years. The dataset, which contains over 2,000 customer purchase history, provides a rich source of information for analyzing the dynamics of customer relationships in the supermarket context.

### **Key Attributes**:


> *PEOPLE*

| # | Feature | Description
| --- | --- | --- 
| 1 | ID | Customer's unique identifier
| 2 | Year_Birth | Customer's birth year
| 3 | Education | Customer's education level
| 4 | Marital_Status | Customer's marital status
| 5 | Income | Customer's yearly household income
| 6 | Kidhome | Number of children in customer's household
| 7 | Teenhome | Number of teenagers in customer's household
| 8 | Dt_Customer | Date of customer's enrollment with the company
| 9 | Recency | Number of days since customer's last purchase
| 10 | Complain | 1 if the customer complained in the last 2 years, 0 otherwise

> *PRODUCT PURCHASE BEHAVIOR*

| # | Feature | Description
| --- | --- | --- 
| 11 | MntWines | Amount spent on wine in last 2 years
| 12 | MntFruits | Amount spent on fruits in last 2 years
| 13 | MntMeatProducts | Amount spent on meat in last 2 years
| 14 | MntFishProducts | Amount spent on fish in last 2 years
| 15 | MntSweetProducts | Amount spent on sweets in last 2 years
| 16 | MntGoldProds | Amount spent on gold in last 2 years

> *PROMOTIONAL ENGAGEMENT*

| # | Feature | Description
| --- | --- | --- 
| 17 | NumDealsPurchases | Number of purchases made with a discount
| 18 | AcceptedCmp1 | 1 if customer accepted the offer in the 1st campaign, 0 otherwise
| 19 | AcceptedCmp2 | 1 if customer accepted the offer in the 2nd campaign, 0 otherwise
| 20 | AcceptedCmp3 | 1 if customer accepted the offer in the 3rd campaign, 0 otherwise
| 21 | AcceptedCmp4 | 1 if customer accepted the offer in the 4th campaign, 0 otherwise
| 22 | AcceptedCmp5 | 1 if customer accepted the offer in the 5th campaign, 0 otherwise
| 23 | Response | 1 if customer accepted the offer in the last campaign, 0 otherwise

> *PURCHASE PLACES*

| # | Feature | Description
| --- | --- | --- 
| 24 | NumWebPurchases | Number of purchases made through the company’s website
| 25 | NumCatalogPurchases | Number of purchases made using a catalogue
| 26 | NumStorePurchases | Number of purchases made directly in stores
| 27 | NumWebVisitsMonth | Number of visits to company’s website in the last month


## **3. PROBLEM STATEMENT**

- **73% of supermarket customers were never accept any campaign** held by the supermarket
- The **Market Strategy** will be formulated in order to help the Supermarket business to adapt its product based on its intended customers from diffent segment of customer
- In other words, instead of wasting money marketing a new product to every single customer in the business's database, the supermarket can determine which customer segment is most likely to buy the product and then market the product solely to that particular group of customers.
- *“Market strategy formulation is similar to navigating a complex terrain; understanding customer shopping behavior serves as the compass that guides us through the labyrinth of choices”*

## **4. DATA CLEANING
- All dtypes are set
- Only one column with null values, it will be dropped since it only weights 1%
- No duplicate data

## **5. DATA PREPARATION
- Renaming several columns to have a clearer vision
- Construct several needed columns that will be helpful in the analysis
- Grouping several values for a particular column to simplify the analysis
- Drop several uneeded columns that will not be used in the analysis

## **6. OUTLIERS HANDLING
- Removing outliers in column Age and Income

## **7. ANALYSIS AND VISUALIZATION**

  *OUTLINE:*

  1. Formulating the analysis by analysing the correlation for several columns
  2. Proportion of supermarket custumers from different demographics
  3. Median Spending of customer from different demographics for the past 2 years
  4. Income Category affecting customer purchase behavior
  5. Best Selling Product

## **8. CONCLUSION AND RECOMMENDATION**

  1. CONCLUSION
     The analysis of the supermarket customer dataset has provided valuable insights into various aspects of customer behavior, purchase preferences, and product consumption. These findings offer actionable insights that can guide marketing strategies and decision-making to enhance customer engagement and satisfaction. Thus, it can significantly impact the overall business success

  2. RECOMMENDATION
     - Income our golden key
         Higher income, more consumptive
        “Single” is our valuable customer which also has a higher income
        They should be targeted with personalised offers when purchase at large scale
        “Is Parent” with low income is less attracted by campaign
        Thus, offers special bundles consisting of several product that is categorized as primary goods
       
     - Optimizing Web Experience
         Lower income, high web visit, but low purchase
         Offer special online deals to target this segment

     - Elevating In-Store Experience
         Since it dominates as the most favoured method
         Layout improvement,  staff training, limited in-store deals

     - Diverse Product Offerings
          Offers time-limited promotion to product that has long freshness date
          e.g Wine, perform a campaign during special event or Feast day (Christmast and new year eve)
          Offers daily promotion to product with limited freshness date
          e.g Meat, Fish, Fruit
          Increase the least product sales
          Sweet, perform a bundles at special day such as Helloween
          Fish, sell only few variety of fish but very popular  such as Salmon, Tuna. 
          Also can add popular seafood such shrimp, crab
          Gold, offers special discount if the customer is celebrating an anniversary 
