# ABDSM
This code is for an agent-based disease spread model which is built on the SydneyGMA activity/travel agent-based microsimulation model to simulate the COVID-19 disease spread. A short explanation of the model is brought here.

Required data and resurces:
1- The daily and cumulative data which are used for the model calibration are reported in  NSW Government (2020). 
2- The code is built on SydneyGMA. SydneyGMA has been originally developed for Toronto, Canada and then it has been transferred to few other cities worldwide. For more information about the model refer to https://tmg.utoronto.ca/doc/1.4/gtamodel/index.html. We cannot make the SydneyGMA publicly available as it is in the discretion of the inventors. Also, this model uses the EMME package for auto and transit assignment as well as estimation of travel time where EMME is not an open source software. Furthermore, we have borrowed the road and transit network of Sydney from “Transport for NSW“ organization, and we are not allowed to share it beyond the research team.   

References:
NSW Government. NSW COVID-19 cases data | Data.NSW. 2020 [cited 18 Nov 2020]. Available: https://data.nsw.gov.au/nsw-covid-19-data/cases
Travel Management Group (TMG). GTAModel V4.0 Introduction | Travel Modelling Group Documentation. 2020 [cited 27 Nov 2020]. Available: https://tmg.utoronto.ca/doc/1.4/gtamodel/index.html
