# Our finances dashboard

This dashboard has been created to assist me to track our expenditure and savings over time. It includes a dashboard to track key expense categories, credit balances, savings, and salary. The structure also enables me to dig further into particular months of expenditure or categories to see why they are increasing or decreasing. 

This version of the dashboard uses randomized data that I have produced based on some of the summary statistics of our actual data, but the end result isn't representative of our expenditure, for an obvious reason. 

There are three key notebooks:

- `fin_dashboard_rand` The dashboard, it includes the plots of the data of interest. 
- `fin_data_cleaning_rand` This is the notebook where I clean the data, and set up dataframes to feed into the plots on the dashboard. 
- `fin_plot_functions` Here I have set up all the plot functions, separating them out from the data cleaning process. 

I have used this format, in an attempt to simplify the analysis, clearly separating the plots (which could be used to present information), and the background code. The original idea with separating out the plots was to see if I could have common plot functions across projects. This did not work out, but the structure here I believe enables the reader to see what is needed. 

A user without much knowledge of jupyter notebooks, or python, could easily load in new csv files in the `fin_data_cleaning_rand` notebook, save the notebook and then run the `fin_dashboard_rand` to see the updated numbers. 
