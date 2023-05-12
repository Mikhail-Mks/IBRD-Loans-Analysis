# IBRD Loans Analysis

This project aims to analyse the loans data from the International Bank for Reconstruction and Development (IBRD), which is a part of the World Bank Group. The data includes information on loan types, amounts, interest rates, repayment status, borrower’s obligations, and more. The analysis is done using Python and Power BI.

## I have delved into the data from 1947 to 2022, uncovering some intriguing findings:

* My investigation revealed that the Fixed-Spread Loan was the most common loan type, accounting for over half of all loans across all regions and sectors. In contrast, the Pool Loan was significantly less frequent, appearing only about one-third as often as the Fixed-Spread Loan.

* I also discovered that the vast majority of loans were either partially or fully repaid, with only a small fraction being cancelled or due. Interestingly, the cancellation rate peaked in 1998 and 2009 but never exceeded 0.5% of the total loan amount. Similarly, the due rate also peaked in 2010 but remained below 0.6% of the total loan amount.

* The interest rates on loans varied over time, with a significant spike in 1986 followed by a drop to zero since 2010. I also noticed a shift in loan types from Single Currency Loans to Fixed-Spread Loans in the late 1990s and early 2000s.

* One standout discovery was that China received the largest amount of loans in 1998, primarily for agriculture and environment projects. In contrast, Latin America received the largest share of loans in 2009-2010, accounting for 35% of all loans during that period. Interestingly, the undisbursed amount of loans was low until 2010, indicating that most loans were disbursed quickly after approval. However, since 2010, the undisbursed amount has increased significantly, suggesting possible delays or challenges in loan implementation.

* My investigation also revealed that IBRD increased its lending activity during the period of 2008-2010, possibly in response to the global financial crisis and its impact on developing countries. This is reflected in the higher amounts of loans approved, disbursed, and outstanding during that time.

* Finally, I uncovered that the exchange adjustment on loans had a negative value in most years, indicating that the US dollar appreciated against most other currencies during that period. The borrower’s obligation on loans peaked in 2010, which could be due to various factors. Further analysis of the specific loan and borrower details would be required to determine the exact cause of this peak.

In conclusion, my investigation into IBRD's loans data revealed some fascinating insights, providing a clearer picture of the lending activities and trends over the years. As a detective of data, I am confident that my findings will assist in future decision-making and planning for the IBRD.

### Code and Visualization

The code for this project is written in Python and can be found in ibrd_loans_analysis.py file. The code performs data cleaning, transformation, aggregation, and analysis using pandas and seaborn libraries.

### The visualization for this project is created using Power BI:
https://www.novypro.com/project/international-bank-for-reconstruction-and-development-loans-analysis

### Data sources:

https://finances.worldbank.org/Loans-and-Credits/IBRD-Statement-Of-Loans-Historical-Data/zucq-nrc3  
https://finances.worldbank.org/Loans-and-Credits/IBRD-Statement-of-Loans-Latest-Available-Snapshot/sfv5-tf7p
