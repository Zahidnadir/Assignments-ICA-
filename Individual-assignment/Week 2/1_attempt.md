1. Initial Dataset Investigation

A. Dataset Overview

The file `teaching_prices_messy.csv` contains price records of different products across two cities. It has "97 rows and 6 columns" : date, item, city, price, unit, and data label.

B. Problems Identified

After examining the dataset, I found the following issues:

1. One duplicate record.
2. One missing price.
3. A price written as `1,250` instead of a standard numeric format.
4. An unusually high price of `9999`.
5. Inconsistent product naming (`oil b` instead of `Oil B`).
6. Conflicting prices for the same date and city under these two product labels.


C. Planned Actions

Issue                                      Planned Action 
         
Duplicate                                Remove the extra record.
Missing price                            Retain and flag it. 
Incorrect formatting                     Convert to numeric and investigate.  
Unusual price                            Retain and verify.
Inconsistent naming                      Investigate before correcting. 
Conflicting records                      Keep both until verified. 


D. Conclusion

The dataset contains several errors that could affect the accuracy of the analysis. I will correct clear errors while keeping questionable values until they can be verified.

E. Attempt-Before-AI Record

-Snapshot filename: 6bd83b0


