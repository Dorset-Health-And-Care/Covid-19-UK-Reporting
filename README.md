# Covid-19-UK-Reporting

Jupyter notebooks demonstrating the use of the UK Governments API for retrieving Covid-19 case and test result data.

API access details are at: https://coronavirus.data.gov.uk/developers-guide

+ Testing downloads and displays test results for the four national of the UK.
+ Covid 19 UK downloads historic cases at Lower Tier Local Authority level and then displays trend graphs for Dorset and BCP, as well as box plot and outlier analysis for all areas to identify those with case rates which may require further investigation.

Minimum requirements
Conda:

+ python >=3.7
+ jupyter
+ numpy
+ pandas
+ plotly
+ tqdm
+ xlrd
Pip only:
+ tsmoothie
+ uk_covid19
