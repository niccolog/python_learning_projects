# Python Learning Projects
Repository for Python Projects related to Learning Data Science &amp; Python. Projects come from both sources like DataQuest or independent analysis on existing datasets.
- DataQuest
- Other Projects (Job Salary search with Ken Jee)
- FIFA 22 Analysis

# DataQuest Projects
# [Project 1 DataQuest: Exploring eBay Car Sales](https://github.com/niccolog/python_learning_projects/blob/main/DataQuest/Ebay_Car_Sales/DataQuest%20Guided%20Project%20-%20eBay%20Cars.ipynb)
## Project Description:
- Analyzed the German Car Sales market on eBay: eBay Kleinanzeigen, a classifieds section of the German eBay website;
- The dataset was originally scraped and uploaded to Kaggle by user orgesleka. The original dataset isn’t available on Kaggle anymore. You can find it via DataQuest
- Original Dataset was edited for learning purposes:
  - Sampled 50,000 data points from the full dataset, to ensure your code runs quickly in our hosted environment;
  - Dirtied the dataset a bit to more closely resemble what you would expect from a scraped dataset (the version uploaded to Kaggle was cleaned to be easier to work with) 
- Practice Data Cleaning with Python & Pandas
- Analyze German car market (most common cars, brands)
- Find patterns affecting car prices

## Project Conclusions:
### Brands/Model
The most common cars are:
1. VW Golf
2. BMW 3 Series
3. VW Polo
4. Opel Corsa
5. VW Passat
VW has 3/5 most popular cars. Mercedes and Audi are both out of the top 5, but Mercedes has two cars in top 10, as many as Opel and BMW, while Audi has only one.
### Repaired vs Damaged Cars
- Cars with no damage or at least no unrepaired damage sell at over 3x the price of cars with unrepaired damages;
- All top cars have repaired price over 3x the damaged one as well, except for Opel Corsa ~2x.   
![](https://github.com/niccolog/python_learning_projects/blob/main/DataQuest/Images/ebay_repaired_car_price.png)

# [Project 2 DataQuest: I-94 Traffic Indicators](https://github.com/niccolog/python_learning_projects/blob/main/DataQuest/Finding_Traffic_Indicators_I94/Traffic%20Indicators%20I-94.ipynb)
## Project Description
- Traffic data on I-94 between Minneapolis & St. Paul, incl. weather & holiday feature 2012-2018;
- The goal of our analysis is to determine a few indicators of heavy traffic on I-94. These indicators can be weather type, time of the day, time of the week, etc. For instance, we may find out that the traffic is usually heavier in the summer or when it snows.

## Project Conclusions
In this project, we looked for indicators of heavy traffic on the I-94 Interstate highway. We can categorize these indicators in 2 types:

Time indicators
- The traffic is usually heavier during warm months (March–October) compared to cold months (November–February).
- The traffic is usually heavier during the day
- The traffic is usually heavier on business days compared to the weekends.
- On business days, the rush hours are ~ 7 and 16.  
![](https://github.com/niccolog/python_learning_projects/blob/main/DataQuest/Images/i94_traffic_distro_monthly.png)
![](https://github.com/niccolog/python_learning_projects/blob/main/DataQuest/Images/i94_traffic_distro_day.png)

Weather indicators (+)
- Shower snow
- Light rain and snow
- Proximity thunderstorm with drizzle

![](https://github.com/niccolog/python_learning_projects/blob/main/DataQuest/Images/i94_weather.png)

# [Project 3 DataQuest: Exit Surveys](https://github.com/niccolog/python_learning_projects/blob/main/DataQuest/Exit%20Survey/Dataquest%20Guided%20Project%20-%20Clean%20and%20Analyze%20Employee%20Exit%20Survey.ipynb)
## Project Description
Data: 
- Exit Surveys from employees of the Department of Education, Training and Employment (DETE) and the Technical and Further Education (TAFE) institute in Queensland, Australia.  

Find hints at answering the following questions:
- Are employees who only worked for the institutes for a short period of time resigning due to some kind of dissatisfaction? What about employees who have been there longer?
- Are younger employees resigning due to some kind of dissatisfaction? What about older employees?

## Project Conclusions
- Established and Veterans seems to have the largest % of unsatisfied in the service_cat column
- We noticed a couple of patterns regarding age while analyzing data:
  - Dete has greater unsatisfaction % across aall categories, with values over 60% in some categories
  - Male employees are disproportionately more unsaftisfied in 60+ age band, while Female employees show the same in the 25 or younger age band
  - Older employees are generally more unsatisfied
![](https://github.com/niccolog/python_learning_projects/blob/main/DataQuest/Images/exit_survey_dete_tefe.png)
![](https://github.com/niccolog/python_learning_projects/blob/main/DataQuest/Images/exit_survey_age_gender.png)
![](https://github.com/niccolog/python_learning_projects/blob/main/DataQuest/Images/exit_surve_age_service.png)

# [Project 4 DataQuest: Story Telling & Data Visualization with Exchange Rates](https://github.com/niccolog/python_learning_projects/blob/main/DataQuest/ExchangeRates/Dataquest%20-%20Storytelling%20Data%20Visualization%20on%20Exchange%20Rates.ipynb)

## Project Description
This short project with Dataquest is designed to visualize Exchange Rates between EUR and other currencies between 1999 and 2020. With this project we are going to import EUR exchange rates from the ECB (European Central Bank), take an exploratory look at the data, then decide what kind of analysis we are going to do.

## Project Conclusions
- EUR-USD under the Last Three complete President mandates
![](https://github.com/niccolog/python_learning_projects/blob/main/DataQuest/Images/exchange_rates_usd.png)
- EUR vs other European Currencies:
  - CHF and GBP have very negatively correlated trends, when one currency gets stronger vs EUR the other one gets weaker. Brexit does not seem to be playing a role in CHF vs GBP correlations.
  - SEK and NOK have very similar trends, the only difference is at the peak of the Financial Crisis and Sovereing Debt the Swedish currency lost more value vs EUR compared to NOK. Could it be because the Norwegian economy is considered more stable, being backed by the sovereign fund (oil funded)?
  - Brexit seems to be a major factor in GBP fluctuation vs EUR since 2016. Another check could be looking into correlations/trends between 2000 and 2015 only.
![](https://github.com/niccolog/python_learning_projects/blob/main/DataQuest/Images/exchange_rates_eur_vs_other_eur_currencies.png)
- EUR vs Main Asian Currencies:
  - SGD follows CNH in its fluctuations vs EUR almost 1:1.
  - KRW is pretty much independent from other Asian currencies behavior and
  - JPY has some correlation to CNH.
![](https://github.com/niccolog/python_learning_projects/blob/main/DataQuest/Images/exchange_Rates_eur_vs_asian_currencies.png)

# Job Salary Search

# FIFA 22 Analysis
