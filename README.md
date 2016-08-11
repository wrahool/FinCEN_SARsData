# FinCEN_SARsData

This is a work-in-progress. This repository tries to aggregate all the publicly available FinCEN (http://www.fincen.gov) data on suspicious activity reports (SARs) in a single, more accessible place.

## Data

All the CSV data files can be found under the data folder. The data is split between two folders because the original data was available in different formats that could not be aggregated.

The 1996-2011 data contains all the filings between the years 1996 and 2011 and are grouped in files identified by the industry under which they were filed and the means used to group them. For example, CC_ByNature.csv contains all the filings that were filed under Credit Cards and Casinos and are grouped by the nature of the filings. 

The 2012- folder contains all the filings since 2012, and are grouped in files that are named according to the industry and the year (20XX) in which they have been filed. Therefore CC12.csv has all the filings made under the Credit Card and Casino industry in the year 2012.

The industry look-up key is as follows:

 - CC - Credit Card Club/Casino
 - DI - Depository Institution
 - H - Housing GSE
 - IC - Insurance Company
 - LFC - Loan or Finance Company
 - MSB - Money Services Business
 - SF - Securities/Futures
 - O -  Other

As of now we are aware that the post-2012 Depository Institutions data isn't complete. [can you list here where there is missing data?]

## Contributors

 - mail [at] subhayan [dot] com
 - pmurck [at] cyber [dot] law [dot] harvard [dot] edu

## License

To the extent any intellectual property rights have been created, the Berkman Klein Center for Internet & Society at Harvard University is the rights holder and these works are licensed under the Creative Commons Attribution 4.0 International Public License license (https://creativecommons.org/licenses/by/4.0/).
