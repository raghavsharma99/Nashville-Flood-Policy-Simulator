# Nashville-Insurance-Mitigation-Comparison-Riverine-Flooding

## Introduction
This repository presents the code and results for a project on the analysis of NFIP insurance policies in minimizing flood losses to Nashville homewoners. It is key to note that 10% Nashville properties are in the 100-yr floodplain and according to FEMA's latest estimates, over 1000 new properties have been added to the floodplain. The Cumberland River flows rightthrough Nashville downtown in May 2010 witnessed a major flooding event when the river breached the 150-yr streamflows and caused over $2 billon losses to private property in Nashville. The objective of this project was to estimate the average annualized losses to homeowners from riverine flooding and also compare flood insurance policies in their potential to minimize flood costs to homeowners.

## Data Used
1. Cumberland Historical Streamflow Record - USGS Streamstats (Station ID: 03431500)
2. 10m DEM Nashville City - USGS
3. 100 damage ratios for 1 to 7ft flood depths (DAMAGE_RATIOS.csv)
4. Insurance terms:
   Insurance A: $1500 annual premium, $1250 deductible
   Insurance B: $1200 annual premium, $5000 deductible
   INsurance C: $900 annual premium, $10000 deductible
   
##  Methodology: 
<img width="704" alt="image" src="https://user-images.githubusercontent.com/83591548/227374113-f89bab42-1e32-45fd-823d-a48486e8d3c2.png">

## Results: 
1. Mean Depth in ROI and Peak Streamflow relationship:
![image](https://github.com/raghavsharma99/Nashville-Insurance-Mitigation-Comparison-Riverine-Flooding/assets/83591548/cdcd211e-002b-42b1-8eae-d15632560214)

2. Peak streamflow and exceedance probability associated with each flood depth:
![image](https://github.com/raghavsharma99/Nashville-Insurance-Mitigation-Comparison-Riverine-Flooding/assets/83591548/e650eef4-8b27-4078-9bcc-359d42553297)

3. 100-yr flow simulation:

![](https://github.com/raghavsharma99/Nashville-Insurance-Mitigation-Comparison-Riverine-Flooding/blob/main/100yrGIFCumberland.gif)

2. Distribution of average annualized cost to homeowner:
![image](https://github.com/raghavsharma99/Nashville-Insurance-Mitigation-Comparison-Riverine-Flooding/assets/83591548/b6d10938-c37c-489a-9b37-a74337fc0387)

3. Average annualized cost to homeowner under 3 insurance scenarios:
![image](https://github.com/raghavsharma99/Nashville-Insurance-Mitigation-Comparison-Riverine-Flooding/assets/83591548/a07e7c61-e3d7-49b8-8db7-505626e514ed)

 
