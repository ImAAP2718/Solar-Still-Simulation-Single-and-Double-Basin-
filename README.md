# Solar-Still-Simulation-Single-and-Double-Basin-
Overview

This project implements a numerical simulation of a solar still for desalination, based on coupled heat and mass transfer mechanisms. The model evaluates thermal interactions between the basin plate, water layer, and glass cover, and estimates the rate of freshwater production under varying solar radiation conditions.The simulation computes temperature evolution and evaporation rates over time, providing both hourly and cumulative water yield.

The model is based on transient energy balance equations applied to key components:

Basin plate
Water layer
Glass cover

The following physical processes are included:

Solar radiation absorption on inclined surfaces
Convective heat transfer between water and glass
Radiative heat exchange between surfaces and surroundings
Conductive heat transfer between plate and water
Evaporative heat transfer and mass flux due to vapor pressure differences

Solar radiation is calculated using geometric relations involving solar declination, hour angle, zenith angle, and surface orientation. The tilted surface irradiance is obtained using standard radiation decomposition models.

Vapor pressure is estimated using empirical relations, and evaporation rates are computed based on temperature-dependent mass transfer correlations.


Key input parameters include:

Latitude and day of year
Surface tilt angle and orientation
Solar clearness index
Ambient temperature
Wind speed (time-dependent)
Material properties (thermal conductivity, heat capacity, thickness)
System geometry (areas and volumes)
Outputs

The model produces:

Water temperature as a function of time
Glass temperature as a function of time
Hourly distilled water output (L/m²)
Total daily freshwater production
Graphical outputs include temperature variation and production trends over time

