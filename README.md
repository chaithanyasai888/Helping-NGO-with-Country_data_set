# Helping-NGO-with-Country_data_set
### The main objective of this project is to classify the countries using some socio-economic and health factors that determine the overall development of the country. Then you need to suggest the countries which the CEO needs to focus on the most.
### Apply Principal component analysis, K-Means Clustering, Hierarchical Clustering.
### Description of the Data set
    1. country: Name of the country
    2. child_mort: Death of children under 5 years of age per 1000 live births
    3. exports: Exports of goods and services per capita. Given as %age of the GDP per capita
    4. health: Total health spending per capita. Given as %age of GDP per capita
    5. imports: Imports of goods and services per capita. Given as %age of the GDP per capita
    6. Income: Net income per person
    7. Inflation: The measurement of the annual growth rate of the Total GDP
    8. life_expec: The average number of years a new born child would live if the current mortality patterns are to remain the same
    9. total_fer: The number of children that would be born to each woman if the current age-fertility rates remain the same.
    10. gdpp: The GDP per capita. Calculated as the Total GDP divided by the total population.
### Two Approaches has done on this data 
    Approach 1 : Including Outliers
    Approach 2 : Exclude outliers
### Final Conclusion
   Among the two conclusion drawn from approach 1 i.e. including ouliers and approach 2 i.e. excluding outliers, approach 1 is the appropriate choice because it includes all the data points including outliers. As per the business requirements, we have to find all the countries which are in direst need of aid i.e. the countries which are having low socio-economic and health factors. Hence we can't exclude any countries from our dataset as it will create a major drawback in our model. For example: let's take an outlier country 'Nigeria' which is having low socio-economic and health factors. If we exclude this outlier from my dataset, we will miss our main objective as it happened with approach 2. So, even though the model was greater than the previous model, we can't use it as it doesn't suits the business needs. Selecting approach 2 means we have to loose many countries in process which is not ideal from business prespective.
