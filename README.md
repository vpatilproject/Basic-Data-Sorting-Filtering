Dataset: Retail Sales Dataset (1,000 transactions, 1 Jan 2023 – 1 Jan 2024) Workbook: Task11_Sorting_Filtering.xlsx | Report: Task11_Project_Report.pdf

Workbook
Summary – the 5 questions with rows, total sales and average
Q1–Q5 – filters used, how to reproduce in Excel, live formula answers, and the filtered + sorted rows (with filter buttons)
Raw_Data – untouched original data (filter buttons on)
Questions and answers
Which transactions reached the maximum Total Amount (2,000), and which category has the most of them?
Filters: Total Amount = 2,000 (the maximum); sort: Product Category A→Z, then Date oldest→newest
Answer: 49 transactions reached the maximum Total Amount of 2,000, together worth 98,000. Electronics has the most (19), then Clothing (17) and Beauty (13).
Which Clothing purchases by Female customers were worth 500 or more, and what did they add up to?
Filters: Product Category = Clothing AND Gender = Female AND Total Amount ≥ 500; sort: Total Amount largest→smallest, then Date oldest→newest
Answer: 61 Clothing purchases by female customers were worth 500 or more. They total 69,700 (average 1,142.62) – about 44.8% of all Clothing sales.
Which Beauty transactions in Q4 2023 (Oct–Dec) had a quantity of 3 or more?
Filters: Product Category = Beauty AND Date between 01-Oct-2023 and 31-Dec-2023 AND Quantity ≥ 3; sort: Date oldest→newest
Answer: 44 Beauty transactions in Q4 2023 had a quantity of 3 or more, covering 149 units and 26,475 in sales (average 601.70).
How many Electronics purchases were made by young customers aged 18–25, and how much did they spend?
Filters: Product Category = Electronics AND Age between 18 and 25; sort: Age youngest→oldest, then Total Amount largest→smallest
Answer: 58 Electronics purchases were made by customers aged 18–25, totalling 26,760 (average 461.38) – 17.0% of all Electronics transactions.
Which high-priced bulk purchases (price 300+ per unit, quantity 3+) were made by Male customers aged 40 and over?
Filters: Gender = Male AND Age ≥ 40 AND Price per Unit ≥ 300 AND Quantity ≥ 3; sort: Date oldest→newest
Answer: 51 bulk, high-price purchases were made by male customers aged 40+, worth 71,000 in total (average 1,392.16) – 15.6% of all sales. They are spread across Electronics (22), Beauty (16) and Clothing (13).
Notes
Raw data kept unchanged; multiple filters combine with AND.
Every Q sheet has a formula check against Raw_Data (all show OK).
Sort = reorders rows; filter = hides rows that do not match (nothing is deleted).
Content
SampleSuperstore.csv

CSV

retail_sales_dataset.csv

CSV
