---
title: "Stochastic Modeling of Weather Series in San Antonio Using an Advanced Weather Generator"
collection: talks
type: "Climate & Simulation"
permalink: /talks/proj-5-2023-11-01-climate
venue: "Climate Modelling - AWEGEN"
date: 2023-11-01
location: "NUS"
---

This project involved the use of the AWE-GEN weather generator to simulate and compare key climate variables for San Antonio, including precipitation, temperature, solar radiation, vapor pressure, and wind speed. The primary objective was to assess how well the generated data replicated observed climate conditions, providing insight into the accuracy and reliability of stochastic weather models in simulating real-world weather patterns.
[Download Slides](http://kingdaxing.github.io/files/Climate_AWEGEN.pdf)


Findings: 
======
Precipitation: The weather generator successfully captured the general frequency of wet and dry days but tended to underestimate the intensity of rainfall events. This discrepancy was addressed by adjusting the Gamma distribution parameters (shape and scale), improving the simulation of extreme precipitation events. A more accurate representation of observed rainfall intensity was achieved by fine-tuning these parameters based on the observed intensity distribution.<br/>
<p align="center">
  <img src='/images/proj-climate-1.PNG' alt='Image Description' width='450'> 
</p>

Temperature: The simulated temperature data generally reflected the expected seasonal cycles, but there was a slight underestimation of extreme temperature values, particularly during heatwaves and cold spells. This was addressed by refining the autoregressive model (AR(1)), adjusting the autoregressive coefficient to capture the persistence of extreme temperatures more effectively. Additionally, the seasonal amplitude and standard deviation were fine-tuned to better match observed temperature variability across different seasons, ensuring a more realistic simulation of temperature extremes.<br/>
<p align="center">
  <img src='/images/proj-climate-2.PNG' alt='Image Description' width='400'> 
</p> 

Solar Radiation: While the simulated solar radiation followed observed trends, the model was less sensitive to variations in cloud cover, particularly on overcast days. To enhance this, adjustments were made to the cloud cover model, specifically refining the Beta distribution parameters to better represent observed cloud cover patterns. This adjustment improved the simulation’s sensitivity to cloud conditions, leading to more accurate radiation values under different weather scenarios.
<br/>
<br/>
In conclusion, this project demonstrates that while the AWE-GEN weather generator effectively simulates the broad features of San Antonio’s climate, adjustments to specific model components are necessary to enhance the accuracy of certain variables. By fine-tuning the parameters related to precipitation, temperature, solar radiation, and wind speed, the model can more closely match observed climate data. 
