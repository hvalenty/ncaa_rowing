# ncaa_rowing
Exploratory study on NCAA women's rowing teams.

## Aim 
Leverage webscraping to seamlessly extract roster and lineups data from NCAA women's rowing teams. Use this information to track lineup changes throughout a season to compare with boat performance data. Beginning the study on Duquense's women's team, where I rowed from 2020-2024. Using this repo as a medium to practice techniques from the UVA MSDS program, on data which interests me.


Progressing the study to the UVA women's rowing team. Using a PDF reader tool to extract 2023-2024 compiled results, and collecting historical placement and time data by hand. The PDF extraction is immensly helpful for lineups, which are separated by boat but then rejoined at dataframe by meet. Once pieces of the analysis are coded, functions are implemented to futher optimize the data extraction.


The skills and techniques implemented here are typically found earluer in the data pipeline, before any analysis is performed. I am manipulating data from its raw form on the internet to a workable format within Python. Jupyter Notebooks allow for quick response handling of smaller code chunks which is helpful for string cleaning and manipulation.

## Techniques
* Web scraping
* PDF text extraction
* Data frame manipulation with pandas
* Text cleaning with string functions
* Regular expression handling 