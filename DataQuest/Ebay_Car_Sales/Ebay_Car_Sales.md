# Ebay Car Sales Project
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
- All top cars have repaired price over 3x the damaged one as well, except for Opel Corsa ~2x
