# 2019 Coronavirus Distribution Visualization


## Step1.Install package and load data from github

* Data: the nCov2019 package by Guangchuang Yu [link](https://github.com/GuangchuangYu/nCov2019)


## Step2. Package structure exploration 

  <img src="images/1%20package%20structure.png">


## Step3.EDA, Data visualization on main epidemic areas

* Global Data, all countries

  <img src="images/2%20Global%20Data.png" width="60%">
  
  <img src="images/9%20worldmap%20with%20China%20breakdown.png" width="60%">


* China Data, all provinces

  <img src="images/3%20China%20data.png" width="60%">
  
  
  <img src="images/10%20china%20map.png" width="60%">


* Number of confirmed cases(global)

  <img src="images/6%20global%20confirmed%20cases.png" width="60%">

* Confirmed cases in Hubei Province, where the epidemic is the most severe

    <img src="images/4%20most%20severe%20province.png" width="60%">
    
    <img src="images/7%20confirmed%20cases%20in%20Huber%20provinces.png" width="60%">
 
* Confirmed cases in Wuhan, the city where the epidemic is the most severe

   <img src="images/5%20most%20severe%20city.png" width="60%">

  
* Number of confirmed cases over time

  <img src="images/11%20confirmed%20case%20over%20time.png" width="60%">
  
  > The sudden change in on Feb.12 was due to a change in the official standard of "confirmed cases'
  
  > taking that into consideration and applying the old standard, the confirmed cases would have been:
  
  <img src="images/12%20(actual)%20confirmed%20cases%20over%20time.png" width="60%">


## Step4. Time series prediction
  <img src="images/13 exponential smoothing TS.png" width="60%">
  
  <img src="images/14 Forecast from HoltWinters.png" width="60%">
