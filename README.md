# Goal

In 2020, we begins with one of the greatest pandemics in modern history, COVID-19. This is no longer a national issue but a worldwide threat and the consequences can make us years to overcome. As a person who was born and raised in Vietnam, I think I can clearly feel the material shortage at medical facilities nationwide, especially in Ho Chi Minh City. Despite all the extremely complicated developments of COVID-19, Vietnam is a country with an impressive anti-epidemic record. Even in China, the outbreak, the epidemic situation is still much better than Western countries, where economic conditions, high quality of medical and also as a destination to treat incurable disease from individuals who come from countries with lower quality such as Vietnam.

I have been inspired to answer the question, **are there any countries lying about their epidemic situation?**  For answering this question, I am going to analyze the relationship between Press-Freedom Index 2020 and COVID-19 situation information each country. 

# Source of data

1. Epidemic data is scraped from [worldometers](https://www.worldometers.info/coronavirus/) on April 6, 2020.

2. Press-Freedom Index 2020 are published by [Reporter Without Boarder](https://rsf.org/en/ranking_table).

# Press Freedom Index

[Press Freedom Index](https://en.wikipedia.org/wiki/Press_Freedom_Index) (PFI) is an annual ranking of countries complied and publish by [Reporter Without Border](https://rsf.org/en) since 2002. The rank score is calculated by how violant the state, the Internet enviorment, cersorship policy,... affect the level of media independence and legislative framework for media, or free flow of information in the Internet. The year of the report is the year the report was released and intends to reflect events in the prior year. 

Please take a note, PFI score is calculated by how violant is in a particular countries, so  _a smaller score on the report corresponds to greater freedom of press._

![](https://github.com/trungtv4597/Covid_19_and_Press_Freedom_Index_Analysis/blob/master/charts/rel_fre_cat.png)

* PFI 2020 compiled and ranked 169 countries và in 6 continents (only if seperating  America into South and North) or 20 regions. 

![](https://github.com/trungtv4597/Covid_19_and_Press_Freedom_Index_Analysis/blob/master/charts/dis_coun_pfi_type.jpg)

* The report classifies countries into 5 situations - Good, Satisfactory, Noticeable, Difficult and Very Serious. But in my work, I renamed them with 5 corresponding levels for easily analyzing - Free, Upper Average, Average, Lower Average, Not Free.

![](https://github.com/trungtv4597/Covid_19_and_Press_Freedom_Index_Analysis/blob/master/charts/his_pfi.jpg)

* The average PFI score is 34.54.

# Press Freedom Index and Epidemic Situation 

## Correlation

![Correlation in Global](https://github.com/trungtv4597/Covid_19_and_Press_Freedom_Index_Analysis/blob/master/charts/general_corr.jpg)

* In Global, countries is higher the PFI score which is having higher number of cases and deaths over 1 million (cases/1m and deaths/1m).

![Correlation in free group](https://github.com/trungtv4597/Covid_19_and_Press_Freedom_Index_Analysis/blob/master/charts/corr_free.jpg)

* In free situation, the lower the PFI score is the higher the cases/1m and deaths/1.

![Correlation in not-free group](https://github.com/trungtv4597/Covid_19_and_Press_Freedom_Index_Analysis/blob/master/charts/corr_not_free.jpg)

* In not-free situation, the correlation is extremely small, that mean number of cases and deaths over 1 million population are independent from Press Freedom score.

## Average Epidemic Situation by Press Freedom Category

![](https://github.com/trungtv4597/Covid_19_and_Press_Freedom_Index_Analysis/blob/master/charts/total_pfi_mean.jpg)

* By average number of cases, deaths, cases/1m and deaths/1m, there is a huge difference between free and upper average (also consider almost free) group with others.

* The anti-epidemic performance of free and upper average group is really when comparing with three other groups whose Press Freedom score is worse.

## By Continent

### Ranking and list of best and worst score each continent

![Rank and list of best-worst pfi score each continet](https://github.com/trungtv4597/Covid_19_and_Press_Freedom_Index_Analysis/blob/master/charts/pfi_con.jpg)

### Compare the best and worst PFI score countries by cases over 1 million population

![](https://github.com/trungtv4597/Covid_19_and_Press_Freedom_Index_Analysis/blob/master/charts/best_score_worse_perf_case.jpg)

* There are four continents have cases/1m population of the best PFI score countries higher than the worst ones. But three from those continents come from bottom four in average PRI score rank, and the PRI score is higher than 30, 

## By Region

### Ranking and list of best and worst score each continent

![](https://github.com/trungtv4597/Covid_19_and_Press_Freedom_Index_Analysis/blob/master/charts/pfi_reg.jpg)

### The best and worst PFI score countries in number of cases over 1 million population

![](https://github.com/trungtv4597/Covid_19_and_Press_Freedom_Index_Analysis/blob/master/charts/best_score_worse_perf_case_reg.jpg)

* There are eleven (over twenty) regions is higher cases/1m of the the best PFI score countries than the worst ones. But 54.6 percent (36.4% from Asia and 18.2% from Africa) of regions come from two worst average PFI score contients.

![](https://github.com/trungtv4597/Covid_19_and_Press_Freedom_Index_Analysis/blob/master/charts/worst_score_worse_perf_case_region.jpg)

* Group of the best PFI score countries, whose cases/1m is lower than the worst ones, is 28.39 average PFI score. Comparing to 35.51 of above group, that means this group is freeer at media.

* In addition to looking carefully at Group I (in figure), whose performance is extremely better than Group II (in figure), is also  worse in average PFI score.

### The best and worst PFI score countries in number of deaths over 1 million population

![](https://github.com/trungtv4597/Covid_19_and_Press_Freedom_Index_Analysis/blob/master/charts/best_score_worse_perf_death_region.jpg)

* There are six regions have deaths/1m of the best PFI score countries are higher than the worst ones. But once again, majority (89.7 percent) of the regions come from three bottom rank of average PFI score continent.

![](https://github.com/trungtv4597/Covid_19_and_Press_Freedom_Index_Analysis/blob/master/charts/worst_score_worse_perf_death_region.jpg)

* Group of the best PFI score countries, whose deaths/1m is lower than the worst ones, is 27.9 average PFI score. Comparing to 36.02 of above group, that means this group is also freeer at media.

### by Total Cases and Deaths

![](https://github.com/trungtv4597/Covid_19_and_Press_Freedom_Index_Analysis/blob/master/charts/case_pareto.jpg)

* Number of countries that contain 80 percent of cases over the world is 14, but thier average PFI score is lower than the rest of the world.

![](https://github.com/trungtv4597/Covid_19_and_Press_Freedom_Index_Analysis/blob/master/charts/death_pareto.jpg)

* The same thing happend to total of deaths, there are only 8 countries take 80 percent of deaths over the world but their average PFI score is really much lower than the rest.
