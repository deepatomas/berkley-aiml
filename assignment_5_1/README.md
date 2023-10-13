**Purpose:** Readme file for Module-5 of Professional Certification of AI/ML course
**Date created:** Oct 11 2023
**Last updated:** Oct 12 2023

**Project description:** The goal of this project is to use what you know about visualizations and probability distributions to distinguish between customers who accepted a driving coupon versus those that did not.

**Project Repository:**

_./data:_ Contains the dataset used for the analysis. This data comes to us from the UCI Machine Learning repository and was collected via a survey on Amazon Mechanical Turk. The survey describes different driving scenarios including the destination, current time, weather, passenger, etc., and then ask the person whether he will accept the coupon if he/she is the driver. Answers that the user will drive there ‘right away’ or ‘later before the coupon expires’ are labeled as ‘Y = 1’ and answers ‘no, I do not want the coupon’ are labeled as ‘Y = 0’. There are five different types of coupons -- less expensive restaurants (under $20), coffee houses, carry out & take away, bar, and more expensive restaurants ($20 - $50).

_./images:_ Contains all plot images generated from the analysis. 
All category plots are named in the format allcoupon* 
Bar plot graphs files are named in the format barcoupon* 

_Code files:_
Module-5.ipynb: Contains analysis for all coupons and for Bar coupons
Module-5-Coffeehouse analysis.ipynb: Contains analysis for Coffee House coupons

**How to navigate analysis code cells within Notebook:**
1. All code cells related to All coupon type analysis begin with the comment text "#Allcoupons"
2. Bar Coupon analysis begin with the comment text "#Barcoupons" 
3. Coffee House Coupon analysis begin with the comment text "#CoffeeHousecoupons"
4. Analysis and Conclusions are posted within the Notebook under "All coupon conclusions", " Bar coupon analysis & conclusions", "Coffee House coupon analysis & conclusions"

**Data Cleaning:**
The following data cleaning steps were taken:
1. Ages below 21 and over 50 were replaced as 20 and 51 and Age column converted to INT
2. Bar column values that were "never" ,"less1", nan were replaced with 0
3. Coffeehouse column values that were "never" ,"less1", nan were replaced with 0
4. CarryAway column values that were "never" ,"less1", nan were replaced with 0
5. RestaurantLessThan20 column values that were "never" ,"less1", nan were replaced with 0
6. Restaurant20To50 column values that were "never" ,"less1", nan were replaced with 0



