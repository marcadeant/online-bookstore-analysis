# Online-bookstore-analysis

For the purporse of my professional training, I worked as Data Analyst for an online bookstore named LaPage (fictional bookstore).
LaPage give me full acces on customer and product's data to build some online-behavior customer's analysis. Analysis allowed to get deeper into our customer's knowledges and reforce our marketing strategies. 
Furthermore, I had acces on transaction's data, meaning that all customer purchased book transaction are stored in it. Data will expose on [Customer, product and transaction data](#)'s section

# Customer, product and transaction data

LaPage was agreed sharing an example of their data. Here, I expose [post-treatment](https://github.com/marcadeant/online-bookstore-analysis/blob/main/Jupyter%20Labs/Post-treatment.ipynb) data I used for buisness Analysis  

1. [Customer example's data](https://github.com/marcadeant/online-bookstore-analysis/blob/main/Post-treatment%20Data/customer_df_clean)
2. [Product example's data](https://github.com/marcadeant/online-bookstore-analysis/blob/main/Post-treatment%20Data/product_df_clean)
3. [Transaction example's data](https://github.com/marcadeant/online-bookstore-analysis/blob/main/Post-treatment%20Data/transaction_df_clean)

# Buisness Analysis

First analysis treated on turnover time's evolution during 2021-2022's sell period. I did basic statistical analysis to identify best/worse sell's period. 
I also did moving average analysis to find out tendancy and seasonnality. More generally, I used Lorenz's Curve to understand how much is customer proportion responsible of profit.

Second analysis used customer and product data to compute statistics based on customer behavior (What kind of client is interested by this product ?)
Customer behavior's analysis can be find [here](https://github.com/marcadeant/online-bookstore-analysis/blob/main/Jupyter%20Labs/Books-sale%20Analysis.ipynb).

In additional, I realized hypothesis's test to make our customer behavior's interpretation true. I used **Pearson**, **Spearman**, **Chi-2** and **Anova** statistical's test with [python framework](https://github.com/marcadeant/all_stats) I developed. 
All hypothesis's tests are available [here](https://github.com/marcadeant/online-bookstore-analysis/blob/main/Jupyter%20Labs/Hyopthesis's%20test.ipynb)
