# assignment_5_1_starter
Berkley AI Course Work Assignment 5.1

This repository consists of a Jupyter Notebook that analyzes an interesting survey taken to find out how likely a customer accept a coupon.

# Introduction
Imagine driving through town and a coupon is delivered to your cell phone for a restaraunt near where you are driving. Would you accept that coupon and take a short detour to the restaraunt? Would you accept the coupon but use it on a sunbsequent trip? Would you ignore the coupon entirely? There are 5 unique types of coupons
* 'Restaurant(<20)'
* 'Coffee House'
* 'Carry out & Take away'
* 'Bar'
* 'Restaurant(20-50)'

# First Segment
In the first segment we analyze one specific coupon type i.e., *Bar*. 
Before starting analysis, we do the data cleaning and fill out the missing values. Our strategy to fill out the missing values is to fill with most 'frequently' used value. Since the missing values aren't too many, this clean up action shouldn't impact the data quality.

First segment analyzes and finds the insights of acceptence ratio of Bar Coupons in different scenarios.
* Patrons who visit bars less than 3 times a month
* Patrons who visit bars at least once a month
  + Over age 25
  + Having Kid a passenger
  + Farming as profession
  + Having Kid a passenger and Widowed
  + Under age 30
  + Goes to restaurant more than 4 times a month and income less than 50K
 
# Second Segment
In the second segment, We first try to find
* Most widely distributed coupons (descending order)
* Most accepted coupons

Among the types of widely accepted and widely distributed coupons, we'll try to find the insights like
* Do the people who frequent the activity, more likely accept the coupons
* People driving in the direction of coupon activity, more likely accept the coupon
* Do passengers impact the coupon acceptence rate in any way, like having kids as passengers make more likely to accept the coupons
* Does the coupon acceptence has any way related to profession

