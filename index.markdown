---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
title: San Francisco, a focused crime story
---

# Background

San Francisco, a city known for its iconic Golden Gate Bridge, vibrant culture and Silicon Valley has long grappled with public safety challenges.

The dataset at hand helps us understand this narrative, through police incident reports from 2003 to May 2018 - helping us gain an insight into the city's battle with criminal activities through quantative measures. Each entry in the dataset is a moment of conflict with the law - capturing not just a snapshot of unlawful acts but visualising the larger story of San Francisco's evovling socio-economic landscape.

Containing 32 unique categories of crime, the ground reality mirrors the challenges and societal shits that San Francisco has faced during the years. The high occurences of drug-related crimes along with incidents of larceny and burgulary shows us the disparity between wealth and poverty on the same blocks. Furthermore, instances of violent crime such as assault and robbery - punctuate the city's narrative with urgent calls and effective policing.

We focus on a particular set of crimes and hope to shed light on the specific challenges they represent. Our objective is to provide a data-driven analysis that not only quantifies the city's struggles with crime but also offers insights into the ground reality among the population.

The radial polar plot captures the 24-hour pattern of prostitution related crimes in San Francisco. Each spoke on the wheel represents an hour of the day, and the length of each spoke indicates the number of incidents reported at that particular time. From that it is immediately clear that this category of crime peaks in the late night to early morning hours of dawn.

<iframe src='sf-polar-plot.html' style="border-width: 0px" width="80%" height="400px"></iframe>

From midnight to 5 AM, there is a noticeable surge in reported incidents and the nocturnal spikes align with the patterns of night-life acitivities - reflecting the increased vulnerability of night time workers. Alternatively, the plot shows a significant drop in reported incidents during daylight illustrating the cyclic nature of this illegal crime.

Transitioning from the dark hours where incidences of prositution are most common - we observe a shift in criminal activity as daylight ascends. The focus moves from individuals to possesions, particularly during the weekends and on Sundays - where the cholorpeth map offers a visual representation of areas with a heightened risk of vehicle theft. The choropleth map illustrates the risk of vehicle theft crime occurance for each district of San Francisco. Darker the red color means higher risk of vehicle theft in that district and vice versa.

Ingleside and it's neighbouring districts - Bayview and Mission, all have a darker red color on the map showcasing them to become hotspots for vehicle theft on sundays.

<iframe src='sf-vehicle-theft-sundays.html' style="border-width: 0px" width="100%" height="500px"></iframe>

This pattern in the data not only underscores the neighobouring communities to stay alert and vigilant but also indicates of a need for law and enforcement authorities to be more alert and present on certain days in certain districts.

<iframe src='sf-crime-category-counts.html' style="border-width: 0px" width="100%" height="400px"></iframe>
