# Comprehensive Open Dataset for NYC Food Environment 
## Exploratory research on the impact of food environment on health outcomes <br/> in NYC neighborhoods

While a lot of work has done to prove what we eat has significant affect on our health, only handcum of effort is put into understanding urban food environment and how it's affecting health outcomes in neighborhood level. 

Major challenges in this area includes:
- Lack of consensus in defining food environment
- sourcing usable datasets (inconsitent gathering and management by the city / private entitiy)
- Gap between constructs of food environment discussed in the literature and the data that’s actually available
- Not all constructs of food environment are measured, some things are just difficult to measure
- Inconsistent mapping of neighborhood code across different data source 


### goals
Leveraging on [NYC Open Data](https://opendata.cityofnewyork.us/) system, we seek to <br/>
i) To construct a comprehensive dataset of food environments in NYC by neighborhood <br/>
ii) To identify crucial components of NYC neighborhoods’ food environments affecting the residents’ health outcomes

You can see each features by neighborhood from the Colab notebook 
e.g.) Farmers Market-Retail Food Outlet Ratio
![image](https://user-images.githubusercontent.com/42717070/166037910-fb42dba8-20b2-43e8-8538-7e3fac8fbebc.png)


### quick results 
We chose Obesity, Diabeties, and Avoidable Adult Hospitalization rate as a health outcome metric, as they are known to highly related to eating habits. 
##### Obesity ![k76qThZsk_8Q2LvfJBL0H2dvieIHWKpgrCwnofQgRDRF_SAimqTxxXCwGS_liz53d4XTNTnQtY8PaHSUlIS9nPUt4Gn8onWyzcLXd2thQw92Zfd5eDY6EXorDUub](https://user-images.githubusercontent.com/42717070/165998781-ecf1ffb1-e32e-4e62-b020-e42983002430.png)
Among the lowest group of obesity rates:  Farmers market: -0.67 Farmers market per Retail Food (per 1000 people) -0.64 Ratio bodega supermarket -0.61

##### Diabetes 
![Is2nGaepZrNms-buQgAXP_RDO_piNPNgBMzqkwS0bxwsvZ5OFClyKWIuGbBIMs-JkZeEtJIj1mXfQmWVoj3bmWcqfDLHuBK6NNzOqMdQTxcB4Z2K4RLX_RtFw3GQ](https://user-images.githubusercontent.com/42717070/166033340-8521a9b9-fbdd-459b-bfb6-5dd3ee13b081.png)

##### Avoidable Adult Hospitalizations 
![MtZM49BHidFdGwNflQ-qdzLmcNw8RU6SNWR4xdc6vMcuyAuaQJLk0oEvG0laEar5F6_0lneIyf0e815qw_NQrG4Fww1hL01xix0bEseBSVYzlKAH0MEN7EedBKXh](https://user-images.githubusercontent.com/42717070/166034641-ea4201a5-d21a-4e4c-9a98-0fc636e9798a.png)

### Included datasets
Public Datasets we gathered and refined here in this dataset inlude:

[Farmers Market](https://data.cityofnewyork.us/dataset/DOHMH-Farmers-Markets/8vwk-6iz2)  
Respresents healthy, fresh food source

[Recognized Shop Healthy Stores
](url)https://data.cityofnewyork.us/Health/Recognized-Shop-Healthy-Stores/ud4g-9x9z
Definition of a healthy store includes more than just availability. Begs the question of if this list of ~370 stores is really inclusive of ALL the healthy stores -- vs ones that opted to participate in the program

[Community Garden
](url)https://data.cityofnewyork.us/dataset/GreenThumb-Garden-Info/p78i-pat6
Respresent healthy, fresh food source 

[Restaurants with A Grade
](url)https://a816-dohbesp.nyc.gov/IndicatorPublic/VisualizationData.aspx?id=2065,719b87,98,Summarize
Proxy of clean and safe restaurant availability

[SNAP locations
](url)https://usda-fns.hub.arcgis.com/datasets/USDA-FNS::snap-store-locations/about
filename in the drive: snap_l "
Proxy of food outlet availiabilty for low income population 


[NYC Public Use Health data
](url)https://www1.nyc.gov/site/doh/data/data-sets/community-health-survey-public-use-data.page
Comprehensive health outcome (Mortality, prevalence of diseases, eating habits...) across NYC neighborhoods 
also includes Bodega to Supermarket Ratio (the lower the healthier)

[Retail Food Stores
](url)https://data.ny.gov/Economic-Development/Retail-Food-Stores/9a8c-vfzj
A listing of all retail food stores which are licensed by the Department of Agriculture and Markets.




Collaboration with Sara Wang and Meyhaa Buvanesh
