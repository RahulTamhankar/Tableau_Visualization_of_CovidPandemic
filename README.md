# Tableau_Visualization_of_CovidPandemic
This is a Tableau Visualization which will show insights on Covid impact and how countries are performing in their vaccination drives

Link to my Tableau Public- https://public.tableau.com/app/profile/rahul.tamhankar3729/viz/RahulProject/Top20CountriesUnderWorldAvg

Introduction-
1)What is COVID ?
Coronavirus disease (COVID-19) is an infectious disease caused by the SARS-CoV-2 virus. Most people infected with the virus will experience mild to moderate respiratory illness and recover without requiring special treatment. However, some will become seriously ill and require medical attention. Older people and those with underlying medical conditions like cardiovascular disease, diabetes, chronic respiratory disease, or cancer are more likely to develop serious illness. Anyone can get sick with COVID-19 and become seriously ill or die at any age. The virus can spread from an infected person’s mouth or nose in small liquid particles when they cough, sneeze, speak, sing or breathe.
2) How can we stop the spread ?
Ever since the outbreak of the pandemic all the world countries worked together to make the vaccine for which can help in breaking the chain of spread. WHO has approved quite a few vaccines now like moderna, Pfizer, covishield etc.Various countries requesting their citizens to actively participate in covid 19 vaccine drives and to take the vaccine on an immediate basis.
3)Covid and its impact on economy-
The toll the COVID-19 pandemic has exacted on the global economy has been significant, with the International Monetary Fund (IMF) estimating that median global GDP dropped by 3.9% from 2019 to 2020, making it the worst economic downturn since the Great Depression. While the global economy was estimated to have recovered in 2021, recovery has been uneven and disparities in vaccine access and coverage could threaten improvement in much of the world. With my research I discovered that the Asian Countries were the worst impacted due to the covid19 outbreak.


Thus, I concluded and collected data from 2 different data sources-
•	https://ourworldindata.org/coronavirus-source-data
•	https://data.adb.org/dataset/covid-19-economic-impact-assessment-template

4) Ambitiousness of the project and Research questions addressed-
My project is aimed to show how different countries are performing in their covid 19 vaccination efforts. It is a great effort taken by different countries to collect data of every Covid case and the countries vaccination efforts. Since the covid 19 outbreak different countries have ramped up their covid vaccination efforts. All the countries with the help of WHO are trying to vaccinate their entire population to reduce the mortality rate of their population. 
My ambition of this project is 
	To help these countries and the world community to get an idea of which countries are leading in their Covid Vaccination drive and which countries need to ramp up their efforts. I wish to show on the world map the same. 
	I also wish to show Top 20 Countries vaccinated along with the world average. I wish to show which countries are below the world average in their vaccination efforts.
	I wish to show total Covid cases everyday for each country. 
	I wish to display an animation which shows people vaccinated on daily basis for each country. 
	I wish to show the number of deaths related to covid 19 everyday since the outbreak. 
	I wish to show the number of deaths related to covid 19 everyday since the outbreak for each continent and its countries.
There is another issue which I have an ambition to solve. This is related to the economy of Asian countries. 
	I want to show how different sectors of economy like Agriculture, Mining, Business, Trade, Hotels, Manufacturing, Transport etc. has been contributing towards the total % of GDP. This can help these developing nations to take active policy measures to improve the performance of the low contributing sectors.
	I also have an ambition to create dashboards to determine the same. 


Methodology-
To fulfill my ambitions, I researched and discovered two extremely informative datasets from the following official websites-
•	https://ourworldindata.org/coronavirus-source-data
•	https://data.adb.org/dataset/covid-19-economic-impact-assessment-template
These 2 datasets are quite exhaustive in nature. The first dataset has various features like Continent, Location, Total Covid cases, Total Vaccinations of population, Total Deaths etc. The second dataset has economic features related to Asian Countries like Name of Economy, Economic Sectors, % of each economic sector of the total GDP etc. The dataset has around 18k rows and 65 columns.
Here is an insight into my datasets-

![image](https://user-images.githubusercontent.com/87760177/212855745-8d7ad18f-3fd1-4626-b9fc-ebdd6b3d6158.png)

![image](https://user-images.githubusercontent.com/87760177/212855777-9a4b208a-f0cd-4954-8abd-163d3b4ecb57.png)


Analysis-
After taking some deep dive into my datasets I decided to use various features from both of my datasets to help me fulfill my ambitions which I mentioned above.
Here is an insight into my visualizations-
	Ambition 1) To help these countries and the world community to get an idea of which countries are leading in their Covid Vaccination drive and which countries need to ramp up their efforts. I wish to show on the world map the same. 
Visualization-

![image](https://user-images.githubusercontent.com/87760177/212855820-1ae05794-fbea-4a96-8b58-ac87e5f961c6.png)

 
Justification- To effectively show which countries are leading and lagging in their covid vaccination I decided to use maps and use a parameter to show all the countries above a specific population say 5,000,000. I also used colors to show which are quite self-explanatory i.e. The greener the Country means it is leading and has vaccinated large number of its population. The red color indicates the countries need to ramp up their vaccination drive.


	Ambition 2) I also wish to show Top 20 Countries vaccinated along with the world average. I wish to show which countries are below the world average in their vaccination efforts.
Visualization-

![image](https://user-images.githubusercontent.com/87760177/212856217-7eecd40d-01dd-4114-b857-f2940a024c73.png)

 
Justification- To show top 20 countries which are leading in Covid 19 Vaccination I used calculated fields, dual axis, filters etc. I also used a constant line which very powerfully cuts the visualization on the world average of 58.62%.
This helps the countries how they are performing in their vaccination drives as compared to the world average.

![image](https://user-images.githubusercontent.com/87760177/212856353-42acc2b0-7e11-48f4-aa8f-e6fbbceb6e3f.png)

 
Justification- To bring the countries which are underperforming the world average I again decided to use filters and dual axis.


	Ambition 3) I wish to show total Covid cases every day for each country. 
Visualization-

![image](https://user-images.githubusercontent.com/87760177/212856395-253e92e7-e1d1-4996-baae-2ee752f160b7.png)

 
Justification- To show the total Covid cases I decided to use Line chart and filter to show the total covid cases for each country.


	Ambition 4) I wish to display an animation which shows people vaccinated on daily basis for each country. 
Visualization-

![image](https://user-images.githubusercontent.com/87760177/212856460-d8fdbabc-5aa2-4ad7-a3d0-0bb83573731f.png)

 
Justification- To fulfill this ambition I decided to us animation using pages in Tableau. I also used filters for each country.

	Ambition 5) I wish to show the number of deaths related to covid 19 every day since the outbreak. 
Visualization-
 
 ![image](https://user-images.githubusercontent.com/87760177/212856518-2a9138dd-125b-442b-8d04-f8ae994d67f8.png)

 
Justification- To show the total Covid cases I decided to use Line chart and filter to show the total covid related death cases for each country.



	Ambition 6) I wish to show the number of deaths related to covid 19 everyday since the outbreak for each continent and its countries.
Visualization-

![image](https://user-images.githubusercontent.com/87760177/212856553-63b7e62a-a9e7-456e-8384-e70b6606381a.png)

 
Justification- To show the total Covid related death cases for each continent and country I decided to use Drill Down for continent and its countries. 


	Ambition 7) I want to show how different sectors of economy like Agriculture, Mining, Business, Trade, Hotels, Manufacturing, Transport etc. has been contributing towards the total % of GDP. This can help these developing nations to take active policy measures to improve the performance of the low contributing sectors.
Visualization-

![image](https://user-images.githubusercontent.com/87760177/212856607-8e7bb6b3-091b-476f-b1cf-d3203134b674.png)

 
Justification- To show the contribution of each economic sector after covid outbreak in Asian Countries. I decided to use Pie chart which is the best tool to show percentages of a whole and represents percentages at a set point in time.  I also used filters which will help to get an insight of each pie chart for every Asian country.


	Ambition 8) I also have an ambition to create dashboards to determine the same. 
Visualization-

![image](https://user-images.githubusercontent.com/87760177/212856653-6a78d8be-6580-49bc-b9d7-27dd4d5f9af0.png)

 Dashboard-
 
 ![image](https://user-images.githubusercontent.com/87760177/212856700-27025928-8d4a-4647-8a0e-e9870ad6910d.png)

 
Justification- Here I decided to make 2 dashboards which I felt were the most important to fulfill the ambitiousness of the project and address the research questions.

I will also be including some more research questions and try to make visualizations which can bring some wonderful insights into such questions and help the world countries fight against Covid-19.


Conclusions-
We can conclude from the visualizations that the African continent is lacking in terms of % of total population vaccinated. We can see that the north American and south American countries are performing quite nicely and are at the forefront of vaccination efforts. South Asian countries are also performing on similar lines to that of the north and south American countries. We can see that the economies of the Asian countries are largely impacted by the covid outbreak and sectors like manufacturing and agriculture were adversely affected by the outbreak.
Additional research questions-
I can also confidently say from the visualizations that the countries are slowly getting their citizens vaccinated. Based on my research there can be additional research questions which can be addressed like how the sectors like tourism, consumptions etc. started their negative contribution to the economy. Other questions like which are the additional factors which contributed to the deaths like age of a person, did the person had any heart disease, was the person diabetic, did the person had smoking habits etc.

