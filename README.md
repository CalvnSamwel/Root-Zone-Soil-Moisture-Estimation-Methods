# Root-Zone-Estimation-Methods
This repository evaluates two methods for estimating Root Zone Soil Moisture (RZSM) from grid surface soil moisture time series data. The methods analyzed are:

## Exponential Low Pass Filter (ELPF)
Cumulative Distribution Function (CDF) Method
These methods were chosen due to their minimal dataset requirements, making them suitable for scenarios with limited data availability. Specifically, both methods can effectively operate with a time series dataset of just 5 years. The case study for this analysis is based on data from the Twente Soil Moisture Monitoring Stations.

## Repository Structure
* Methodology: Contains detailed descriptions and the theoretical background of both methods. Summarizes the design and approach used in the study.
* Code: Demonstrates the steps for applying both ELPF and CDF methods, including code examples and instructions for use.
Summary of Methods
=> Exponential Low Pass Filter (ELPF)
The ELPF method smooths the time series data to filter out high-frequency variations, providing a more stable estimation of RZSM.

=> Cumulative Distribution Function (CDF) Method
The CDF method transforms the soil moisture data to match a reference distribution, allowing for estimation of RZSM based on statistical properties.

## Evaluation and Results
The methods were evaluated using the following metrics:

## Residual Measure (RMSE)
Linear Correlation Coefficient
Results indicate that the sequential application of the CDF method followed by the ELPF method yielded the most accurate RZSM time series datasets. Among the two individual methods, ELPF significantly outperformed CDF.



## References 
* Albergel, C., ¨ Udiger, C. R., Pellarin, T., Calvet, J.-C., Fritz, N., Froissard, F., Suquia, D., Petitpa, A., Piguet, B., & Martin, E. (2008). Hydrology and Earth System Sciences From near-surface to root-zone soil moisture using an exponential filter: an assessment of the method based on in-situ observations and model simulations. Hydrol. Earth Syst. Sci, 12, 1323–1337. www.hydrol-earth-syst-sci.net/12/1323/2008/

* Wagner, W., Lemoine, G., & Rott, H. (1999). A Method for Estimating Soil Moisture from ERS Scatterometer and Soil Data. Remote Sensing of Environment, 70(2), 191–207. https://doi.org/10.1016/S0034-4257(99)00036-X

* Wang, C., Fu, B., Zhang, L., & Xu, Z. (2019). Soil moisture–plant interactions: an ecohydrological review. Journal of Soils and Sediments, 19(1), 1–9. https://doi.org/10.1007/S11368-018-2167-0/METRICS
