---
layout: page
title: Canopy Stomatal Conductance Estimation
description: 
img: assets/img/agwat25.jpg
importance: 1
category: Stomata
related_publications: true
---
## **Improved estimation of stomatal conductance by combining high-throughput plant phenotyping data and weather variables through machine learning**

<br>

#### Abstract

Stomatal conductance ($g_s$) quantifies the rate of exchange of carbon dioxide for photosynthesis and water vapor for transpiration between plant leaves and the atmosphere. $g_s$ is usually measured by handheld devices like porometers, and readings are manually taken in the field, which is time-consuming and labor-intensive. In this study, we investigated the use of high-throughput phenotyping (HTP) data combined with weather data to estimate $g_s$ through machine-learning (ML) modeling. The experiment was conducted in a research field equipped with an HTP platform in 2020 and 2021 involving maize, sorghum, soybean, sunflower, and winter wheat. Weather variables including dew point temperature, wind speed, air temperature, solar radiation, and relative humidity were collected by an onsite weather station. Plot-level canopy temperature, soil temperature, and seven vegetation indices were acquired using a thermal infrared camera, a multispectral camera, and a visible near-infrared spectrometer integrated on the HTP platform. Three supervised ML methods (Partial Least Squares Regression (PLSR), Random Forest Regression (RFR), and Support Vector Regression (SVR)) were employed to train the estimation models for $g_s$, and model performance was evaluated by Coefficient of Determination ($R^2$) and Root Mean Squared Error (RMSE). The result showed that RFR and SVR outperformed PLSR in $g_s$ modeling. The RFR model achieved $R^2$ of 0.63 and RMSE of 0.16 $mol\,m^{-2}\cdot s^{-1}$ with the combination of phenotyping data and weather data. It outperformed the model using only the weather data ($R^2 = 0.35$ and RMSE=0.21 $mol\,m^{-2}\cdot s^{-1}$), or the model using only the phenotyping data ($R^2 = 0.46$ and RMSE=0.19 $mol\,m^{-2}\cdot s^{-1}$). This result suggested that high-throughput plant phenotyping data effectively complement weather data in estimating $g_s$ rapidly and non-destructively through ML. With the wide adoption of HTP technologies in aerial and ground-based platforms, this research provides a practical framework to estimate $g_s$ at large scale for crop breeding and irrigation management.t

#### Results

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/agwat2025_both.jpg" title="example image" class="img-fluid" %}
    </div>
</div>
<div class="caption">
    Stomatal conductance estimation based on the combined sensor-based phenotypic data and weather data as model inputs using random forest regression. (A) All crop types. (B) Maize. (C) Sorghum. (D) Soybean. (E) Sunflower. (F) Winter wheat.
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/agwat2025_spider.jpg" title="example image" class="img-fluid" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/agwat2025_weather.jpg" title="example image" class="img-fluid" %}
    </div>
</div>
<div class="caption">
    Stomatal conductance estimated based on the sensor-based phenotypic data only (left) and weather data only (right). (A) All crop types. (B) Maize. (C) Sorghum. (D) Soybean. (E) Sunflower. (F) Winter wheat.
</div>

#### Conclusion

The study employed three ML algorithms to estimate gs of five crops using near real-time, sensor-based plant phenotypic data and weather data. Combining the plant phenotypic data with weather variables significantly improved the prediction accuracy of gs, with the model testing R2 of 0.63 (increased from testing R2 of 0.46 and 0.35 with each data set alone). This result indicated the usefulness of sensor-based plant phenotypic data in boosting the accuracy of plant gs modeling and estimation. Because these sensor-based plant phenotypic data could be acquired rapidly and relatively inexpensively, thanks to the advancement in HTP, this study provides a rapid method to quantify canopy gs more accurate than relying on weather variables alone. In terms of ML algorithms, nonlinear RFR and SVR models outperformed the linear PLSR models, suggesting intrinsic nonlinear relationships between leaf gs and the estimator variables, as well as the complex control and feedback mechanisms among these variables. The plant phenotypic data in our study was collected from the NU-Spidercam platform. However, the approach described in this study could be readily used for UAVs or other ground platforms with similar sensors mounted. Rapid and accurate estimation of plant gs, as demonstrated in this study, have implications on applications such as screening for drought-tolerant genotypes and precision irrigation management.

More details can be found in {% cite agwat2025 %}

