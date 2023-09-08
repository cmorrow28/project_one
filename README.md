# Group 7 Project One

All codes are derived from lecture notes, Pandas library and ChatGPT.

Project: COVID-19 Vaccination Effectiveness
Project Description
In this project, we will look at how effective the COVID-19 vaccinations were on factors such as hospitalisations, confirmed cases and mortality rates.

Team Members:
- Geoffrey Pang
- Cayley Morrow
- John Porretta

Research Questions to Answer

1.Australia: were vaccinations effective?

2. How have COVID-19 vaccinations affected??
   a. Australia: New Cases vs New Deaths
   b. Australia, Israel & Sweden: ICU patient admissions, confirmed cases and mortality rates

3.Does a difference in GDP Per Capita affect COVID-19 cases (using WorldBank API)?
   - first world (Australia)
   - second world (Poland)
   - third world (Sudan) – based on political and social aspects.

4.How effective was using different vaccines?
   - Israel (Pfizer only), China (SinoVax, SinoPharm) and Australia (AstraZ, Moderna, Pfizer)


Our Data sets are taken from this two sources:
1. Our World In Data - contains all the latest Covid19 data from around the world.
https://github.com/owid/covid-19-data/blob/master/public/data/owid-covid-codebook.csv
The description of the dataset is given here https://github.com/owid/covid-19-data/tree/master/public/data

2. World Bank API to get GDP per capita
https://datahelpdesk.worldbank.org/knowledgebase/topics/125589-developer-information

Data Processing.
1. Selectice columns are taken form the csv file from Our World in Data.  Depending on the required plots, some groupby month was done with aggregate function of summation and mean were done.
2. GDP Per Capita was gathered from World Bank API.


Final Conclusion¶
- Vaccination appears to be effective in controlling the spread of the COVID-19 virus. However, this could be coincidental.
- Different vaccinations seem to work. However, none of the vaccinations had much of an effect against the spread of Omicron.
- Covid19 spread has decreased significantly since 2020.
- Vaccinations are only one part of the response to COVID-19, there are too many other contributing factors.
- It is not conclusive that vaccinations have been effective in controlling the spread of the virus.
