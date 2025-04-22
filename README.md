# Nashville-Insurance-Mitigation-Comparison-Riverine-Flooding

## Introduction
This repository contains the code, data, and results for an analysis of National Flood Insurance Program (NFIP) policies and their effectiveness in reducing flood-related financial losses for homeowners in Nashville, Tennessee.

Approximately 10% of properties in Nashville lie within the 100-year floodplain, and over 1,000 additional properties have recently been designated at risk by FEMA. This highlights a growing need to evaluate how well current flood insurance options mitigate risk.

The Cumberland River, which runs through downtown Nashville, experienced a historic flood event in May 2010, exceeding 150-year streamflows and causing over $2 billion in damages. This project aims to:

Estimate the average annualized flood losses to homeowners from riverine flooding.

Evaluate the cost-effectiveness of three different flood insurance policies.
## Data Used
1. Cumberland River Historical Streamflow Records
Source: USGS StreamStats (Station ID: 03431500)

2. 10-meter Digital Elevation Model (DEM) for Nashville
Source: USGS National Map

3. Damage Ratios by Flood Depth
Source: `DAMAGE_RATIOS.csv` — includes 100 depth-damage pairs for 1 to 7 ft inundation depths

Insurance Scenarios Analyzed:

Insurance A: $1,500 annual premium, $1,250 deductible

Insurance B: $1,200 annual premium, $5,000 deductible

Insurance C: $900 annual premium, $10,000 deductible
   
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

 
