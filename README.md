#Foster care houses - New York


## Overview

For this project I used a dataset with information about the annual foster care and children protective services for New York, available in Kaggle. This data includes basic data on child protective services(CPS) and foster care by county. I had access to the number of children for each criteria, and also the care days for each type of foster home.
The final project is available in my Tableau Public repository (link available in Resources).


## Sheets

Main_Dashboard:
-Final project dashboard, featuring the number of children for each criteria (including the indicated CPS reports), and the number of care days for each type of Foster Home/Facility. Filters for every year between 1994-2017 as well as for all counties in New York are also available.

Map(main):
-Map for every County(aliases) in New York.

Numb_children(main):
-Number of children for every year between 1994-2017 for each county and criteria (Admissions, Discharges, Children in care, Children served).

Foster_homes(main):
-Number of care days for every year between 1994-2017 for each county and type of Foster Home/facility.

### Adittional graphics:

Numb_children_treemap(main):
-Comparison(by size) of the number of children served for every County in New York.

Numb_children_map(NY/nNY):
-Comparison of the number of children served between New York city(alone) and the remaining counties(grouped).

Foster_homes(NY/nNY):
-Same analysis as for Foster_homes(main). Comparison of the number of care days between New York city(alone), and the remaining counties(grouped).

Numb_children(NY/nNY):
--Same analysis as for Numb_children(main). Comparison of the number of care days between New York city (alone), and the remaining counties(grouped).

Numb_children(%):
-Same analysis as for Numb_children(main), but in percentage.


## Insights

-Aprox 65.43% of the total number of children served belong to New York City.
-Over the years, a general decrease of adoptions was verified, which may be the cause of the increase of the supervised independent living foster children (also called young adults, because they live on their own), .
-There many report of children abuse/maltreatment between 2006-2011. These results match with the increase of care days obsrved for 'Other' foster home facilities (these other facilities include skilled nursing, residential treatment, specialized schools, and more), which suggest that these kids may have entered these type of Foster Home.


## Future perspectives

-More information is required for a much deeper and detailed analysis (number of children by age and sex, and number of social workers per foster home are some examples). 
-Same data for every county in the USA for a more powerful comparison and solution planning.
-Would be interesting to have more detailed information about the reasons why children enter the foster-care system in order to implement a Pareto rule, to identify the main problems over the years and, most importantly, plan a strategy and solutions. For example: until 2005, more than 80% of children enter the USA foster-care system due to parental substance abuse(https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3505234/), which continued to increase over the years, as shown in a report for alcohol and drugs use disorders(https://ourworldindata.org/grapher/alcohol-drug-use-disorders-share-total-disease?). Reducing or trying to control the substance abuse may substancially decrease the number of occurrences. 


## Resources

Final Dashboard: https://public.tableau.com/profile/joan.concha#!/vizhome/Fosterhomes_NewYork/Main_Dashboard

Dataset: https://www.kaggle.com/new-york-state/nys-children-in-foster-care-annually?select=socrata_metadata.json
