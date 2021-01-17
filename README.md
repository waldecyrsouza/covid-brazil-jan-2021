# covid-brazil-jan-2021

All covid deaths in Brazil per city

First of all, my deepest feelings to all the people who were or are being impacted in some way by COVID19.

--- Introduction ---

This Jupyter Notebook presents the effort to gather, assess, clean and analize, the covid data in brazil per city. The main data is available at:
Covid data: https://www.kaggle.com/unanimad/corona-virus-brazil. Version used: 305
Brazil population: https://www.ibge.gov.br/estatisticas/downloads-estatisticas.html. Estimativas_de_população -> Estimativas_2020 -> Estimativas_dou_2020.xls


According to the sources above, the data contains information about population, covid cases and deaths in 2020 per city in Brazil.

The main objective of this script is to compare all the covid deaths per million people in each city and in the biggest city. Also, there were created plots of the deaths curves in São Paulo, Rio de Janeiro and Manaus. This last one is facing a helth public creasis right now (jan/2021).

--- Libraries used ---

numpy
pandas
matplotlib.pyplot
matplotlib.dates


--- Files in the repository ---

brazil_covid19_cities.csv - This data has information about all covid cases and deaths in Brazil since the day of the first suspect case: Jan/30/2020

estimativa_dou_2020.csv - 2020 population estimates  per city according do The Brazilian Institute of Geography and Statistics (Portuguese: Instituto Brasileiro de Geografia e Estatística; IBGE)

Covid_brasil_version_01-17-2020 Jupyter Notebook with the code created.

Plots created by the Jupyter notebook (.JPG):
- manaus_plot
- rio_de_janeiro_plot
- sao_paulo_plot
- top_10_deaths_per_million_biggest_cities_plot
- worst_10_deaths_per_million_cities_plot


--- Results ---

Considering all the cities, the top 10 highest deaths per million occured in small cities. Curvelândia/MT is the top 1, a city of 5241 people that has 239 deaths, so 45.602 deaths per million people.

Another approach, taking in account only the 100 major cities in Brazil showed that Rio de Janeiro/RJ is the one with more deaths per million inhabitants: 2.373.

The moving average (considering 7 days) in São Paulo and Rio de Janeiro are in ascending curve since november/2020. It seems like the second wave of Covid outbreak is on course.
In Manaus, It is in extremely ascendent curve since december/2020.


The data provided has so many useful information and many other questions can be made and answered.


Special thanks to Raphael Fontes for gathering and uploading this data at Kaggle.
