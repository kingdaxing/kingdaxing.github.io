---
title: "Rainfall-Runoff Analysis by QGIS, WFLOW.py & Artificial Neural Network Models"
collection: talks
type: "QGIS & Scripts"
permalink: /talks/proj-3-2023-12-01-hydrology
venue: "CDE"
date: 2023-12-01
location: "NUS"
---

This personal exercise involves three methods to build rainfall-runoff models using observational data, spatial data, and parameters to estimate flooding events: 1) Flow direction and potential flooding areas are analyzed using GRASS tool in QGIS; 2) a fully-distributed hydrological model is developed with wflow.py, integrated with QGIS; 3) an ANN Long Short-Term Memory (LSTM) model is trained in Python, and a Multilayer Perceptron (MLP) model was trained in R. <br/>
Overall, this project strengthens my skills in dataset processing using scripts (Python & R), and in creating DEMs to represent spatial data, further enhancing my ability to analyze shoreline morphology using remote sensing data and integrating ANN machine learning models.

Sub-Project 1: DEMs and Rainfall-Runoff Analysis in QGIS
======

The personal assignment involves processing a Digital Elevation Model (DEM) and conducting hydrological analysis for the Kent Ridge Catchment, which was set up to collect hydrological data and develop a rainfall-runoff model. It includes using both low-resolution CSV data and high-resolution ASC raster data. Additionally, the high-resolution DEM are analyzed to identify natural drainage, flow direction, and flow accumulation points. <br/>
<p align="center">
  <img src='/images/proj-hydro-1-1.png' alt='Image Description' width='500'> 
</p> 
Finally, Kent Ridge catchment data story is created using Tableau. 
[Slides in Tableau](https://public.tableau.com/app/profile/x.p1712/viz/KentRidgeCatchmentstory_PANXINXIN/Story1?publish=yes)


Sub-Project 2： Rainfall-Runoff Response Modelling in wflow.py Integrating QGIS
======

The group assignment involves assessing the impact of rainfall events on two DEMs of the same catchment, reflecting changes due to the construction of COM4 at NUS. Using wflow.py, an open-source hydrological modeling tool, the rainfall-runoff response for both the original and modified catchments are simulated. DEMs are pre-processed in QGIS and inputted into wflow, with runoff coefficients modified for land use changes. The model is run for rainfall events of varying intensity to compare performance as model calibration and validation. Results are analyzed to understand COM4’s impact on catchment response and compared to standard return periods. <br/>
<p align="center">
  <img src='/images/proj-hydro-2.PNG' alt='Image Description' width='600'> 
</p> 
The final results are shown in the presentation.
[Download Slides](http://kingdaxing.github.io/files/Rainfall-Runoff-WFLOW.pdf) 


Sub-Project 3：Artificial Neural Networks (ANNs) Modelling for Prediction
======

The task compares the performance of Long Short-Term Memory (LSTM) networks trained in Python and Multi-Layer Perceptron (MLP) trained in R for time series prediction. LSTM showed better accuracy and stability, especially for capturing peak runoff values and overall trends. It also proved more efficient for shorter time predictions, making it the preferred choice for forecasting rainfall-runoff events in the catchment. <br/>
<p align="center">
  <img src='/images/proj-hydro-3.PNG' alt='Image Description' width='500'> 
</p> 
[Download Report & Scripts](http://kingdaxing.github.io/files/Rainfall-runoff-modelling-using-ANN.pdf) 
