# UPI-Transaction-Count-Dashboard-FY25-26-Interactive-Dashboard-creation-using-Power-BI-
### Project Objective
The payments analytics team wants a single comprehensive report UPI-Transaction-Count-Dashboard-FY25-26 (Interactive Dashboard creation using Power BI)

Tracking UPI transaction counts and volume distribution for FY 2025-26. This allows management to monitor monthly volume trends, track percentage contribution per month, identify peak/trough transaction periods, and evaluate quarter-over-quarter growth across the financial year.

## Note :
Due to data privacy and company confidentiality policies, raw datasets, customer records, and the original workbook are proprietary and cannot be shared publicly.

### Dataset used
Monthly UPI transaction aggregate data for FY 2025-26 (April 2025 to March 2026)
Fields: Month, Quarter, Transaction Count (Millions), Total Volume Share (%), Cumulative Volume



Questions (KPIs)
- What is the total transaction volume recorded across FY 2025-26?
- How do transaction counts vary on a month-by-month basis throughout the year?
- Which month recorded the highest transaction count and contribution percentage?
- Which month experienced the lowest transaction volume?
- How does performance trend across quarters (Q1 to Q4)?
- What is the monthly percentage contribution relative to the total yearly transaction volume?

Dashboard Interaction

-<a href="https://github.com/Abhijeetpatil-1998/UPI-Transaction-Count-Dashboard-FY25-26-Interactive-Dashboard-creation-using-Power-BI-/blob/main/UPI%20Transaction%20Count%20Dashbaord%20(Month%20wise%20Growth).jpeg">View Dashboard</a>

## Process
- Checked raw transaction logs for data integrity, missing monthly entries, and verified numerical scale consistency (Millions/Billions).
- Cleaned and structured the dataset to standardize date formats, quarterly labels (Qtr 1 to Qtr 4), and volume units.
- Created data models and DAX measures (Total Transaction Volume, Monthly % Contribution, QoQ Growth %, Peak Month Indicator).
- Designed a combo chart visual combining bar representations for absolute monthly counts (M) with trend line overlays for percentage contribution (%).
- Assembled key callout KPI cards and embedded quarter slicers to enable dynamic filtering across Q1, Q2, Q3, and Q4.

Dashboard
![UPI Transaction Count Dashbaord](https://github.com/Abhijeetpatil-1998/UPI-Transaction-Count-Dashboard-FY25-26-Interactive-Dashboard-creation-using-Power-BI-/blob/main/UPI%20Transaction%20Count%20Dashbaord%20(Month%20wise%20Growth).jpeg)

### Project Insight
- Total Volume: A aggregate of 4.3 Billion (4.3bn) UPI transactions were processed during FY 2025-26.
- Peak Month: July recorded the highest transaction volume of the year at 398M transactions, representing 9.25% of total yearly volume.
- Lowest Month: February experienced the weakest performance with 314M transactions, contributing 7.76% to the annual total.

### Quarterly Performance:
- Q1 (Apr–Jun): Showed steady upward momentum growing from 350M (8.11%) in April to 383M (8.89%) in June.
- Q2 (Jul–Sep): Peaked in July (398M) before experiencing a drop to 339M (7.87%) in September.
- Q3 (Oct–Dec): Demonstrated steady stabilization ranging between 348M (8.08%) in October and 355M (8.24%) in December.
- Q4 (Jan–Mar): Saw a temporary dip in February (314M) followed by a strong fiscal year-end recovery in March reaching 360M (8.36%).

### Final Conclusion

The UPI transaction growth pattern reflects strong digital adoption with mid-year peak activity in July and a fiscal year-end surge in March. To optimize server load and banking infrastructure capacity, operational teams should prepare for peak demand during Q2 (July peak) and Q4 year-end settlements. Marketing and merchant acquisition teams should focus on driving consumer engagement during historically low periods like September and February to smooth out transaction volume fluctuations across quarters.

### Tools Used
- Power BI Desktop (Data Modeling, DAX, Custom Combo Charts, Visual Slicers)
- Microsoft Excel (Data cleaning & validation)
