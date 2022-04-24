# Amazon_Vine_Analysis

## Overview of the Analysis
Amazon reviews are a key influencer for customers and potential customers looking into products for sale on the website.  The Amazon Vine program was designed to "recruit" the most trusted reviewers active on the site to carry (hypothetically) a stronger influence for other users buying products.  This raises the question of whether or not the Vine program is truly influencing Amazon users.
After piping the dataset (in this case musical instruments) through an ETL process, the transformed data can be examined and a desision can be made (based on one dataset) as to whether the program is influencial or not.

## Results

![image](https://user-images.githubusercontent.com/19878877/164945983-1fa34c02-e2dd-438e-b31f-fb17325def95.png)

![image](https://user-images.githubusercontent.com/19878877/164952032-814457bc-0555-4ddd-a5cf-1bc378e6bcc1.png)

### Number of Vine versus non-Vine reviews
- Vine members produced 60 ratings of instruments overall
- Non-vine members produced 14,477 ratings of instruments overall

### Number of 5-star reviews in the cases of Vine AND non-Vine
- Vine members gave 34 5-star ratings of the above ratings
- -Non-vine members gave 8,212 5-star ratings of the above ratings

### Percentage of 5-star reviews in the cases of Vine AND non-Vine
- Vine members gave a percentage of 56.67 % of 5-star instrument reviews
- Non-vine members gave a percentage of 56.72 % of 5-star instrument reviews


## Summary
In this particular dataset, there is no difference in the reviews between Vine and Non-vine members.  With rounding, there are 57 % 5-star ratings in both cases.  That being said, one can usually trust the instrument-manufacturing companies to produce high-end products.  To expand on this observation one can look at the other star ratings for consistency.
- 4-star:  27% vs. 19%
- 3-star:  15% vs. 9%
- 2-star:  2%  vs. 5%
- 1-star:  0%  vs. 11%

One can notice differences of course - most notable in 4-star reviews - but inconsistently different.  A proper statistcal analysis is due.  In addition, one may consider generating different orders and combinations of current data (bootstrap-like) or randomly selected smaller sects of the volunteer dataset.  The difference between 60 votes (Vine) and 14,477 (Non-vine) is greatly significant and makes pulling out true conclusions difficult.

