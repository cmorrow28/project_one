# project_one

All codes are derive from lecture notes and ChatGPT.

Project: COVID-19 Vaccination Effectiveness
Project Description
In this project, we will look at how effective the COVID-19 vaccinations were on factors such as hospitalisations, confirmed cases and mortality rates.

Team Members:
- Geoffrey Pang
- John Porretta
- Cayley Morrow

Research Questions to Answer
1.How have COVID-19 vaccines affected? (world comparison)?
a. Australia: New Cases vs New Deaths
b. Australia, Israel & Sweden: ICU patient admissions, confirmed cases and mortality rates?

2.Does a difference in healthcare expenditure affect COVID-19 cases (using WorldBank API)?
- first world (Australia, Israel, Sweden, Japan, UK, USA, Singapore)
- second world (Russia, Albania, Serbia, Poland, Romania)
- third world (China, Syria, North Korea, Saudi Arabia, Yemen, Sudan, Burundi, Iran, Vietnam) – based on political and social aspects.

3.Australia: Was vaccination effective?

4.How effective was using different vaccines?
Israel (Pfizer only), China (SinoVax, SinoPharm) and Australia (AstraZ, Moderna, Pfizer)


Our Data sets are taken from this two sources:
1. One World In Data - contains all the latest Covid19 data from around the world.

https://github.com/owid/covid-19-data/blob/master/public/data/owid-covid-codebook.csv
the description of the dataset is given here https://github.com/owid/covid-19-data/tree/master/public/data
2. World Bank API to get GDP per capita

https://datahelpdesk.worldbank.org/knowledgebase/topics/125589-developer-information

Data Processing.
1. Selectice columns are taken form the csv file from One World in Data.  Depending on the required plost, some groupby month was done with aggregate function of summation and mean were done.
2. GDP Per Capita and Population data were taken from World Bank API since the csv file have the same value for population for each year.


Final Conclusion¶
- Vaccination seem to be effective in controlling the spread of the Covid19 virus. However, this could be coincidental.
- Different vaccines seem to work. However, none of the vaccines was able to protect against the Omnicron spreading.
- Covid19 spread has more or less stopped.
- It is not conclusive that vaccinations have been effective in controlling the spread of the virus.
