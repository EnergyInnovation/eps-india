---
layout: page
title:	"India EPS Version History"
---
This page tracks updates that have been made with each version of the India Energy Policy Simulator.

### **3.1.3 - March 5, 2021**

* Updated to model platform 3.1.3
* Added pumped hydro as a power plant type
* Various input data updates, such as power plant costs, demand response and battery storage potential, and COVID-19 recession impacts 

### **2.1.2 - July 10, 2020**

* Fixed minor formula error in variable "Potential RPS Qualifying Electricity Output" and its BAU equivalent
* Updated scaling methodology in indst/BIFUbC and bldgs/BCEU
* Adjusted values in elec/SYC, elec/BCRbQ, elec/BPMCCS, and elec/BRPSPTY to align model outputs with historical 2018 and 2019 data
* Adjusted qualifying sources for the Clean Electricity Standard policy and enabled the "Expand Carbon-free Electricity Standard Qualifying Definitions"

### **2.1.1 - June 9, 2020**

* Updated to version 2.1.1


### **1.4.2-v3 - June 10, 2019**

* Fixed an error where building components energy use was under-reported (bldgs/BCEU)
* Fixed transposed "Consumers" and "Other Industries" labels on "Direct Cash Flow Changes (by Actor)" graph in web app 

### **1.4.2-v2 - Dec 21, 2018**

* Fixed error in fuel economy of passenger and freight LDVs due to misinterpretation of unit definition in source data (trans/BNVFE, trans/SYFAFE, trans/BHNVFEAL)
* Added open burning of agricultural residues to the model (indst/BIFUbC)
* Removed erroneous value for biomass combustion in “other industries” category (indst/BIFUbC)
* Pollutant emissions intensities for biomass burned in industry now are used to represent open burning of agricultural residues (fuels/PEI)
* Pollutant emissions intensities for industry, buildings, and electricity updated to use better, India-specific values (fuels/PEI)
* Quantity of biomass use in buildings updated to use better source (bldgs/BCEU)
* Removed web app policy lever for energy efficiency standards policy applied to agriculture, as agriculture energy use now is used to represent open burning of agricultural residues rather than fuel use by the agriculture industry

### **1.4.2 - Oct 29, 2018**

* Initial Release
