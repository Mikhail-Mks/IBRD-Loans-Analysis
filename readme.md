# IBRD Loans Analysis

This project aims to analyze the loans data from the International Bank for Reconstruction and Development (IBRD), which is a part of the World Bank Group. The data covers the period from 1947 to 2022 and includes information on loan types, amounts, interest rates, repayment status, borrower’s obligations, and more. The analysis is done using Python and Power BI.

## Key Findings

Some of the key findings from the analysis are:

* The most common loan type is Fixed-Spread Loan, which accounts for more than half of all loans and is dominant across all regions and sectors. The second most common loan type is Pool Loan, which is about three times less frequent than Fixed-Spread Loan.

* Most loans are either partially repaid or fully repaid, with only a small fraction being cancelled or due. The cancellation rate peaked in 1998 and 2009, but never exceeded 0.5% of the total loan amount. The due rate also peaked in 2010, but remained below 0.6% of the total loan amount.

* The interest rate on loans has varied over time, with a noticeable spike in 1986 and a drop to zero since 2010. The loan time has also changed over time, with a shift from Single Currency Loans to Fixed-Spread Loans in the late 1990s and early 2000s.

* China received the largest amount of loans in 1998, mainly for agriculture and environment projects. Latin America received the largest share of loans in 2009-2010, accounting for 35% of all loans in that period.
The undisbursed amount of loans was very low until 2010, indicating that most loans were disbursed quickly after approval. However, since 2010, the undisbursed amount has increased significantly, suggesting that some loans may have faced delays or challenges in implementation.

* IBRD increased its lending activity during the period of 2008-2010, possibly in response to the global financial crisis and its impact on developing countries. This is reflected in the higher amounts of loans approved, disbursed, and outstanding in that period.

* The exchange adjustment on loans, which represents the difference between the US dollar equivalent of the loan at the end of the period and at the beginning of the period due to exchange rate fluctuations, had a negative value in most years. This means that the US dollar appreciated against most other currencies during that period. The exchange adjustment had its lowest value in 2010, indicating a sharp appreciation of the US dollar in that year.

* The borrower’s obligation on loans, which represents the outstanding balance of the loan as of the end of the period in US dollar equivalent, had a peak in 2010 as well. This could be due to several factors, such as an increase in the loan amount or an extension of the repayment period. Alternatively, it could be due to changes in exchange rates or difficulties in making payments by some borrowers. Further analysis of the specific loan and borrower details would be required to determine the exact cause of this peak.

* The portion of loan sold to a third party after 1981 was zero. This means that IBRD did not sell any of its loans to other lenders or investors after that year.

* The amount due to a third party was also zero. This means that IBRD did not owe any money to other lenders or investors for its loans.


### Code and Visualization

The code for this project is written in Python and can be found in ibrd_loans_analysis.py file. The code performs data cleaning, transformation, aggregation, and analysis using pandas and seaborn libraries.
The visualization for this project is created using Power BI. It consists of several charts and tables that show various aspects of the loans data.
