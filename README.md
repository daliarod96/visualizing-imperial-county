# Exploratory Data Analysis of the 2021 American Community Survey using the Census API on R

I grew up in Calexico, California in the county of Imperial. Calexico is a small town with a population of about 40,000 thousand people. The closest we have to a metropilis in Imperial County is El Centro, a slightly larger town with a Panda Express, an In-N-Out, an IHOP, and a shopping mall (the fanciest store is a Dillards). 

<center><img src="https://github.com/daliarod96/census-api-EDA/assets/79605544/bf5acde6-e7d1-4f66-bd09-a83abba698f5" width="75%" height="75%" class="center"></center>

Imperial County is right next to the US-Mexico border so it has a very large Latino population. It actually has the largest concentration of Latinos out of any county in California. California has a lot of Latinos overall, being the second largest group after White people. 

<img src="https://github.com/daliarod96/census-api-EDA/assets/79605544/501952f2-eecc-4e25-a516-093b9ca24735" width="75%" height="75%" class="center">

<img src="https://github.com/daliarod96/census-api-EDA/assets/79605544/353c3f33-af6a-424b-816a-a565868dad66" width="75%" height="75%" class="center">

Calexico, where I grew up, is made up of over 95% Latinos. As a child, I was very confused by my school textbooks that talked about the US as a diverse country and a "melting pot" of cultures. The place where I grew up in was not very diverse. Aside from my four Asian friends (1 Korean, 3 Chinese), I had never met anyone who was not Latino (especifically Mexican) until I started my undergraduate studies at UCLA in 2015. 

![race_distribution_imperial](https://github.com/daliarod96/census-api-EDA/assets/79605544/13c7eda1-f043-451d-bb97-7eca9949b16d)


There is a large percentage of people in Imperial County that are currently living in poverty. It is one of the poorest counties in all of California. Coincidentally (not), counties with large concentrations of Latinos are associated with higher levels of poverty.

![latinos_california_map](https://github.com/daliarod96/census-api-EDA/assets/79605544/aaf2f3ec-147a-4c32-b8f2-db1c21e15034)
![poverty_rate_line_latino](https://github.com/daliarod96/census-api-EDA/assets/79605544/6e35b438-6b2f-4ecf-8ed5-cee296e7b24f)


15.5% of Latinos in California are living under the poverty line in comparison to 8.7% of White people. In Imperial County, poverty rates are higher, with 22.3% of Latinos living in poverty in comparison to 10% of White people. Latinos, Indigenous people, Hawaiian Natives, Pacific Islanders, Black people, and an unspecified "Other" are the populations that drive the statewide poverty line upwards. Poverty rates for Asian people in California are low. However, this standalone fact does not mean that Asian people have ceased to experience other forms of racisms. 

![below_poverty_by_race](https://github.com/daliarod96/census-api-EDA/assets/79605544/ad7ffd96-27b8-4c96-8c5c-1593ff82a193)

One possible reason for high poverty rates for Latinos in Imperial, and California as a whole, is low wages. Although the median household income does not tell us much about disparity, a closer look at family incomes for White people and Latinos in California reveal large differences between the two populations.

![median_income](https://github.com/daliarod96/census-api-EDA/assets/79605544/f0a6da8f-4871-4941-92c8-9be3297e2905)


Almost twice as many white families in California make over $100,000 a year (59.2%) in comparison to Latino families (31.6%). Over half of White families in California are bringing in over $100,000. Over half of Latino families in California are bringing in less than $60,000. In Imperial County, 16.5% of families are surviving on less than $20,000 a year in comparison to 6.8% of White families. 

![family_income_ca_imp](https://github.com/daliarod96/census-api-EDA/assets/79605544/d24b773c-c8cd-465d-9201-315cc036ae33)


Latinos are the group with the highest concentration of residents without a high school diploma (33%) and the lowest concentration of residents with a Bachelor's degree or higher (14.9) after the unspecified "Other." Only 4.7% of White people are not high school graduates and 45.4% have at least a Bachelor's degree. White people are 6x less likely to not hold a high school diploma and 3x more likely to have a university degree than Latinos.

![educational_attainment_CA](https://github.com/daliarod96/census-api-EDA/assets/79605544/e17019f3-f3a7-4e4a-8903-09d386f04c33)
![educational_attainment_imp](https://github.com/daliarod96/census-api-EDA/assets/79605544/4759229b-84ac-41ae-ae63-ffb39200ebae)


Counties with high concentrations of residents without a high school diploma are associated with higher concentrations of poverty.

![pvt_less_than_hs](https://github.com/daliarod96/census-api-EDA/assets/79605544/bf5fb6b1-dafb-4bfc-8012-928ef64ee7a2)

An associate's degree does not provide relief from poverty. 

![pvt_associates](https://github.com/daliarod96/census-api-EDA/assets/79605544/64fd21a9-8f9f-41bb-9dd4-4d2b1eca3f4d)


Bachelor's degrees (or higher) are associated with lower poverty rates.

![pvt_bachelor](https://github.com/daliarod96/census-api-EDA/assets/79605544/f3c797e7-fcfc-4f53-9eb1-6951e6e110c3)


The Imperial County needs a lot of help. The data shows that Imperial County is not an isolated case, but one of many examples of systemic oppression that Latinos face in the United States. Low wages and low educational attainment are two factors keeping Latinos in poverty. 

What can we do to help? 

We can start by making changes to the Census itself. 

The census does not have an isolated cateogry for Latinos. The category is called "Hispanic or Latino." Hispanic and Latino are not interchangeable terms. Hispanic refers to anybody who speaks Spanish. This includes people from Spain, who are European and mostly White. The reason why so many Latinos speak Spanish is because we were colonized by Spain. Spanish people, being European, are not at all perceived in the same way as Latinos. That is the reason why someone like Rosalia, who is Spanish, is the first person to popularize reggaeton, a Puerto Rican genre, to non-Latino audiences in the United States and worlwide. Spanish people are not Latinos. Our cultures differ in everything but the language that we speak. We should not pigeonholed into the same category. Furthermore, not all latinos speak Spanish. Brazilian people speak portuguese. 

Afrolatinos exist and need to be accounted for in the census. The census separates White Latinos and Non-Latino White people to account for the White Latino population. However, it provides no separation between Black Latinos and Non-Latino Black people. Afrolatinos clearly face unique prejudices. For one, the census does not provide them with their own category.

The category "Other" needs to be clarified. Despite them only making 3% of the California population, "Other" face similar forms of oppression that Latinos, Black, Indigenous and Hawaiian or Pacific Islander people face in the United States. We need to know who they are. "Other" is not enough. 

