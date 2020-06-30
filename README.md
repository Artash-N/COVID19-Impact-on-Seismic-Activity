# COVID19-Impact-on-Seismic-Activity
COVID19 may have closed doors of my school. But the windows to education remained open. I used the period of the lockdown to learn more about the environment around me and measure the changes happening. These included changes in street noise, pollution levels, traffic count and seismic vibrations. 

Seismic vibrations or vibrations of the ground are caused by natural and human made activities. Natural activities include earthquakes, vibrations, ocean waves, and wind. Human made activities includes vibrations caused by transport, construction activities, railways, and even passage of big ships close to the shore.

COVID19 lockdown led to virtual stoppage of many activities including ground, air and water transporation, construction activities, closure of businesses, closure of education and government institutions. The number of people and vehicles on the road decreased dramatically. All this would have impacted the human made seismic vibrations. 

Could these changes be noticed by seismometers which record ground vibrations?

To enable more people to measure changes around them I wrote this Tutorial. This tutorial would allow anyone to measure changes in seismic vibrations through analysis of publically available data from seismic stations located around the world. It would allow comparing changes that occurred in their city before, during and after the lockdown.

It would take less than one hour for most people to complete the Tutorial. However downloading the data needed to complete this tutorial may take a few hours, depending on the internet connection. Seismic data is very rich in resolution. The ground stations collect upto 100 or more readings per second. To measure the changes happening in ground vibrations due to COVID19 would require studying the trend in vibrations and that would span several weeks or months. Hence a large dataset, running upto one billion values needs to be worked upon to conduct analysis.

**This Tutorial would allow user to conduct several step by step analysis:**

    1. Calculating the Probabilistic Power Spectral Densities from the raw siesmic data
    
    2. Extracting seismic vibrations of the targeted frequency ranges
    
    3. Using the Root Mean Square function to compute seismic displacement over time
    
    4. Creating a trend-line to clearly visualize the changes in seismic vibration during the lockdown
    
    5. Calculate the percentage change in seismic vibrations from before to during the lockdown
    

Do remember, seismic stations by design are meant to study natural vibrations. Thus most of them are constructed far away from cities. Thus not all seismic stations may be sensitive enough to changes in vibrations caused by lockdown in the cities.


All data used in the tutorial is retreived from Incorporated Research Institutions for Seismology (IRIS.edu), through the python ObsPy library. Many of the analysis steps went through in this tutorial were edited from a tutorial by Thomas Lecocq : https://github.com/ThomasLecocq/SeismoRMS
