---
layout: single
title: "Projects"
permalink: /projects/
author_profile: true
---

{% include base_path %}

### <a target="_blank" href="https://e6.ijs.si/ParallelAndDistributedSystems/projects/eles_mn/"> Uncertainty module for DTR</a>

High-voltage transmission lines represent an important segment of the electric power transmission network. They not only connect the production and consumption network in Slovenia, but also connect the Slovenian transmission system with neighboring ones. In the last years, we witness an extremely rapid development of the electricity market and services, mainly due to the inclusion of renewable electricity resources in the network. System operators in recent years have faced challenges in how to ensure maximum transmission capacity of the system to satisfy market needs, while maintaining operational safety and permissible impact on the environment. A great help in the decision-making process was introduced with the Dynamic Thermal Rating (DTR) – an instrument to monitor the temperatures of conductors by using weather and load forecasting to estimate their future trend in order to calculate the ampacity of a transmission line. However, the introduction of DTR raises a number of questions related to the accuracy and uncertainty of the results of thermal assessment and the level of acceptable risk and its management. In order to prepare a conceptual solution forSchematic representation of the operative DTR uncertainty estimation Schematic representation of the operative DTR uncertainty estimation estimating the uncertainty of the dynamic thermal flow as a result of the DTR process, we examined the weather and transmission conditions on two locations (routes) in Slovenia: Podlog and Bevkov vrh. We first analyze the measurements and forecast of weather variables, including ambient temperature, wind speed and direction, and solar irradiation.

We analyze the dependence of the forecast error from the age of the forecast and have concluded to divide the forecast into three types according to age, namely current weather assessment, short-term forecast and medium-term forecast, where there is no significant difference in quality between short-term and medium-term forecast. With the help of conductor surface temperature measurements, weather data measurements and predicted weather data, we estimate the error of the DTR process itself. The results reveal that most of the error is due to the error in the weather forecast. In the analyses, we observed that the influence of the ambient temperature and the solar irradiation on the thermal current distribution is negligible, while the influence of wind speed and direction is not. We also investigate the influence of different types and emissivity of transmission lines and have concluded that it is not negligible either. Based on the results of data analysis, we built a conceptual solution for estimating the uncertainty of thermal flow based on Monte Carlo random simulations. Using the Monte Carlo method, we randomly sample the error of the input weather conditions, and use the DTR model to calculate the thermal current distribution.


## Ongoing projects

- [Medusa: coordinate free meshless method implementation](http://e6.ijs.si/medusa/)
    <br>C++ library for solving PDEs with an intuitive syntax.
- WingDesigner (courtesy of NOVA Vertriebsgesellschaft m.b.H):
    <br>Software for development and simulation of paragliders.
