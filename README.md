# The Relationship between Press Freedom Index 2020 and COVID-19 Situation each Country

**Table of contents:**

1. [Goal](#goal)
2. [Source of Data](#soucre_of_data)
3. [Press Freedom Index](#pfi)
4. [Press Freedom Index and Epidemic Situation](#relationship)
  
    1. [Correlation](#correlation)
    2. [Average Epidemic Situation by Press Freedom Category](#average)
    3. [By Continent](#continent)
    
        1. [Ranking](#con_rank)
        2. [The Best and worst PFI Score each Continent Number of Cases over 1 Million Population](#best_worst_pfi_each_continent)

    4. [By Region](#region)
    
        1. [Ranking](#reg_rank)
        2. [The Best and worst PFI Score Nations each Region Number of Cases over 1 Million Population](#by_cases/1m)
        3. [The Best and worst PFI Score Nations each Region Number of Deaths over 1 Million Population](#by_deaths/1m)
  
    5. [By Number of Cases and Deaths](#"total)   
  
5. [Conclusion](#conclusion) 
6. [Limitation and Improvement](#limit)
7. [Author](#author)
  

# Goal <a name="goal"></a>

In 2020, we begins with one of the greatest pandemics in modern history, COVID-19. This is no longer a national issue but a worldwide threat and the consequences can make us years to overcome. As a person who was born and raised in Vietnam, I think I can clearly feel the material shortage at medical facilities nationwide, especially in Ho Chi Minh City. Despite all the extremely complicated developments of COVID-19, Vietnam is a country with an impressive anti-epidemic record. Even in China, the outbreak, the epidemic situation is still much better than Western countries, where economic conditions, high quality of medical and also as a destination to treat incurable disease from individuals who come from countries with lower quality such as Vietnam.

I have been inspired to answer the question, **are there any countries lying about their epidemic situation?**  For answering this question, I am going to analyze the relationship between Press-Freedom Index 2020 and COVID-19 situation information each country. 

# Source of Data <a name="soucre_of_data"></a>

1. Epidemic data is scraped from [worldometers](https://www.worldometers.info/coronavirus/) on April 6, 2020.

2. Press-Freedom Index 2020 are published by [Reporter Without Boarder](https://rsf.org/en/ranking_table).

# Press Freedom Index <a name="pfi"></a>

[Press Freedom Index](https://en.wikipedia.org/wiki/Press_Freedom_Index) (PFI) is an annual ranking of countries complied and publish by [Reporter Without Border](https://rsf.org/en) since 2002. The rank score is calculated by how violant the state, the Internet enviorment, cersorship policy,... affect the level of media independence and legislative framework for media, or free flow of information in the Internet. The year of the report is the year the report was released and intends to reflect events in the prior year. 

Please take a note, PFI score is calculated by how violant is in a particular countries, so  _a smaller score on the report corresponds to greater freedom of press._

1.

![](https://github.com/trungtv4597/Covid_19_and_Press_Freedom_Index_Analysis/blob/master/charts/rel_fre_cat.png)

* PFI 2020 compiled and ranked 169 countries và in 6 continents (only if seperating  America into South and North) or 20 regions. 

2.

![](https://github.com/trungtv4597/Covid_19_and_Press_Freedom_Index_Analysis/blob/master/charts/dis_coun_pfi_type.jpg)

* The report classifies countries into 5 situations - Good, Satisfactory, Noticeable, Difficult and Very Serious. But in my work, I renamed them with 5 corresponding levels for easily analyzing - Free, Upper Average, Average, Lower Average, Not Free.

3.

![](https://github.com/trungtv4597/Covid_19_and_Press_Freedom_Index_Analysis/blob/master/charts/his_pfi.jpg)

* The average PFI score is 34.54.

# Press Freedom Index and Epidemic Situation <a name="relationship"></a>

**Notice the abbreviation:**

    * PFI: Press-Freedom Index 2020
    * Cases/1m: number of cases over 1 million of population
    * Deaths/1m: number of deaths over 1 million of population

## Correlation <a name="correlation"></a>

Each circle represents a nation in the Index of Press Freedom. Correlation plot in deaths/1m is fewer number of nations because there are no death by virus in these nations.

1. In global

![Correlation in Global](https://github.com/trungtv4597/Covid_19_and_Press_Freedom_Index_Analysis/blob/master/charts/general_corr.jpg)

* The global correlation intends to decrease in both cases, that means countries is higher the PFI score which is having higher number of cases and deaths over 1 million.

2. In the free nations

![Correlation in free group](https://github.com/trungtv4597/Covid_19_and_Press_Freedom_Index_Analysis/blob/master/charts/corr_free.jpg)

* This correlation intends to increase in both cases, that means the worse PFI is the higher cases/1m and deaths/1m are in the free nations.

3. In the not-free nations

![Correlation in not-free group](https://github.com/trungtv4597/Covid_19_and_Press_Freedom_Index_Analysis/blob/master/charts/corr_not_free.jpg)

* In not-free situation, the correlation is extremely small, that means number of cases and deaths over 1 million population are independent from PFI score. Or we can say that PFI score doesn't reflect epidemic situation in all those not-free nations.

## Average Epidemic Situation by Press Freedom Category <a name="average"></a>

![](https://github.com/trungtv4597/Covid_19_and_Press_Freedom_Index_Analysis/blob/master/charts/total_pfi_mean.jpg)

* By average number of cases, deaths, cases/1m and deaths/1m, there is a huge difference between the free and upper average (also consider almost free) group with others. 

* Or this show us the average - lower average - not-free groups are having extremely good anti-epidemic performance.

## By Continent <a name="continent"></a>

### Ranking and List of The Best and Worst Score each Continent <a name="con_rank"></a>

We are going to rank all Contients by their average PFI and list the best and worst score nations each continent. 

![Rank and list of best-worst pfi score each continet](https://github.com/trungtv4597/Covid_19_and_Press_Freedom_Index_Analysis/blob/master/charts/pfi_con.jpg)

### The Best and worst PFI Score Nations each Continent Number of Cases over 1 Million Population <a name="best_worst_pfi_each_continent"></a>

Let compare those countries in the list above.

![](https://github.com/trungtv4597/Covid_19_and_Press_Freedom_Index_Analysis/blob/master/charts/best_score_worse_perf_case.jpg)

* There are four continents are having the nation with the worst PFI that is doing better in anti-epidemic.

* But three from those continents come from bottom four in average PRI continent rank, and the PRI score is higher than 30.

## By Region <a name="region"></a>

### Ranking and List of The Best and Worst Score each Region <a name="reg_rank"></a>

We are doing the same thing, but this time we rank regions

![](https://github.com/trungtv4597/Covid_19_and_Press_Freedom_Index_Analysis/blob/master/charts/pfi_reg.jpg)

### The Best and Worst PFI Score Countries each Region Number of Cases over 1 Million Population <a name="by_cases/1m"></a>

1. 

![](https://github.com/trungtv4597/Covid_19_and_Press_Freedom_Index_Analysis/blob/master/charts/best_score_worse_perf_case_reg.jpg)

* There are eleven (over twenty) regions whose the best PFI score nations are higher cases/1m than the worst ones. 

* But 54.6 percent (36.4% from Asia and 18.2% from Africa) of regions come from two worst average PFI score contients. 

2.

![](https://github.com/trungtv4597/Covid_19_and_Press_Freedom_Index_Analysis/blob/master/charts/worst_score_worse_perf_case_region.jpg)

* Group of the best PFI score countries, whose cases/1m is lower than the worst ones, is 28.39 average PFI score. Comparing to 35.51 of the group above, that means this group is freeer at media.

* In addition to looking carefully at Group I (in figure), whose performance is extremely better than Group II (in figure), is also  worse in average PFI score, 24.61 compares to 33.21. 

### The Best and Worst PFI score Countries in Number of Deaths over 1 Million Population <a name="by_deaths/1m"></a>

1.

![](https://github.com/trungtv4597/Covid_19_and_Press_Freedom_Index_Analysis/blob/master/charts/best_score_worse_perf_death_region.jpg)

* There are six regions whose the best PFI score nations are higher deaths/1m than the worst ones. But once again, majority (89.7 percent) of the regions come from three bottom rank of average PFI score continent.

2.

![](https://github.com/trungtv4597/Covid_19_and_Press_Freedom_Index_Analysis/blob/master/charts/worst_score_worse_perf_death_region.jpg)

* Group of the best PFI score countries, whose deaths/1m is lower than the worst ones, is 27.9 average PFI score. Comparing to 36.02 of the group above, that means this group is also freeer at media.

* By [cases/1m](#by_cases/1m) and [death/1m](#by_deaths/1m), it's obviously the worse PFI score the better anti-epidemic performance.

## By Number total of Cases and Deaths <a name="total"></a>

1.

![](https://github.com/trungtv4597/Covid_19_and_Press_Freedom_Index_Analysis/blob/master/charts/case_pareto.jpg)

* Number of countries that contain 80 percent of cases over the world is 14, but thier average PFI score is better than the rest of the world.

2.

![](https://github.com/trungtv4597/Covid_19_and_Press_Freedom_Index_Analysis/blob/master/charts/death_pareto.jpg)

* The same thing happend to total of deaths, there are only 8 countries take 80 percent of deaths over the world and their average PFI score is really much better than the rest.

# Conclusion <a name="conclusion"></a>

There is no direct evidence that can indicate the low FPI nations lying about their COVID-19 situation. But we have a right to question their transparency of publishing information because there is, through this report, a quite strong correlatin between having good performance in epidemic and bad Fress-Freedom Index.

# Limitation and Improvement <a name="limit"></a>

The biggest limitation in this report is only one national index to compare with four indicator of epidemic situation. So the best way to improve this report is collecting more data to extract insight, evidence or causal relationship.

# About Me <a name="author"></a>

My name is Duc-Trung Tran,

* [Github](https://github.com/trungtv4597/)
* [LinkedIn](https://www.linkedin.com/in/trung-tran-4b1501180/)
* Email: trungtv4597@gmail.com

A year ago, I started my first science project, self-driving application, to try to utilize all the knowledge I had gained from university. In the development process, I applied artificial neural network technology, and soon it was all my interest.

I have been inspired by the story of Moneyball, where people were using the power of programming and statistics to change the unfair game, to win with the lowest budget. I know we can apply that instance to improve our life, our business or our performance. That's why I decided to leave the IoT laboratory, where I was a collaborator, to focus all my resources to pursue a career in data science.

