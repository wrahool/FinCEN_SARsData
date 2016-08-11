# FinCEN_SARsData

The Financial Action Task Force has recommended that "Countries should maintain comprehensive statistics on matters relevant to the effectiveness and efficiency of their AML/CFT systems. This should include statistics on the STRs [suspicious transaction reports] received and disseminated; on money laundering and terrorist financing investigations, prosecutions and convictions; on property frozen, seized and confiscated; and on mutual legal assistance or other international requests for cooperation." (see -> http://www.fatf-gafi.org/media/fatf/documents/recommendations/pdfs/FATF_Recommendations.pdf, see also -> http://www.fatf-gafi.org/media/fatf/documents/reports/AML-CFT-related-data-and-statistics.pdf).

This repository attempts to aggregate all the publicly available FinCEN (http://www.fincen.gov) data on suspicious activity reports (SARs, the US equivalent of STRs) in a single, easily accessible place. Please note this is still a work in progress and we welcome pull requests or corrections.

## Data

All the CSV data files can be found under the data folder. The data is split between two folders because the original data was available in different formats that could not be aggregated.

The 1996-2011 data contains all the filings between the years 1996 and 2011 and are grouped in files identified by the industry under which they were filed and the means used to group them. For example, CC_ByNature.csv contains all the filings that were filed under Credit Cards and Casinos and are grouped by the nature of the filings.

The 2012- folder contains all the filings since 2012, and are grouped in files that are named according to the industry and the year (20XX) in which they have been filed. Therefore CC:12.csv has all the filings made under the Credit Card and Casino industry in the year 2012.

The industry look-up key is as follows:

 - CC - Credit Card Club/Casino
 - DI - Depository Institution
 - H - Housing GSE
 - IC - Insurance Company
 - LFC - Loan or Finance Company
 - MSB - Money Services Business
 - SF - Securities/Futures
 - O -  Other

As of now we are aware that this archive isn't complete. The data for the years 2010-2011 could not be gathered for any of the industries, because the data sources were corrupted. Moreover, the data for post-2012 Depository Institutions is also not complete: records filed under the following regulatory bodies, for the years 2014 and 2015, couldn't be collected owing to a number of system errors that we encountered during the process.

 - the CFTC
 - the FHFA
 - the OCC

## Contributors

 - mail [at] subhayan [dot] com
 - pmurck [at] cyber [dot] law [dot] harvard [dot] edu

## License

To the extent any intellectual property rights have been created, the Berkman Klein Center for Internet & Society at Harvard University is the rights holder and these works are licensed under the Creative Commons Attribution 4.0 International Public License license (https://creativecommons.org/licenses/by/4.0/).
