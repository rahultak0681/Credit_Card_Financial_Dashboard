# project insights 
## WoW change: 
### Revenue increased by 28.8%, 
### Total Transaction Amt & Count increased by xx% & xx%
### Customer count increased by xx%
## Overview YTD:
### Overall revenue is 57M
### Total interest is 8M
### Total transaction amount is 46M
### Male customers are contributing more in revenue 31M, female 26M
### Blue & Silver credit card are contributing to 93% of overall transections
### TX, NY & CA is contributing to 68%
### Overall Activation rate is 57.5%
### Overall Delinquent rate is 6.06



IncomeGroup = SWITCH(
 TRUE(),
 'public cust_detail'[income] < 35000, "Low",
 'public cust_detail'[income] >= 35000 && 'public cust_detail'[income] <70000, "Med",
 'public cust_detail'[income] >= 70000, "High",
 "unknown"
)
