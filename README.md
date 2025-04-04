# athletic_sales_analysis
Module 5 Homework


Resources Used:

-------------------------

Google Colab
- Used as guide for combining dataframes (Part I: " pd.concat...join='inner' ")
- Used as guide for initial groupby (Part II: " ...df.groupby(['region', 'state', 'city'])['units_sold'].sum().reset_index() ")
- Used as guide for initial pivot table/aggfunc (Part II: " pd.pivot_table(combined_sales_df, values='units_sold', index=['region', 'state', 'city'], aggfunc='sum') ")
  - By extension, rest of assignment used initial coding guides as outline
- Part V: Forgot how to use \ to break up words when entering 'Women\'s Athletic Footwear'

ChatGPT
- Used as guide for researching aggfunc and resampling into bins
