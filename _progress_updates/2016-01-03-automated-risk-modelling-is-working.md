---
title: Automated risk modelling is working
subtitle: A special thing
layout: post
post_date: '2016-11-03'
image: 
---

Using log-Gaussian Cox process (LGCP) models, implemented using R-INLA, we showed it was possible to model passive surveillance case data (geolocated back to household and classified as locally acquired) from Swaziland to produce monthly smoothed maps of predicted incidence. 

Elevation, temperature, vegetation, wetness, distance to waterbodies and incidence of imported cases were all used to explain and predict where local cases occurred. These risk maps help to visualize the underlying risk that gave rise to the individual cases, accounting for where people live. These maps also account for variation in treatment seeking behaviour; data show that people who live far from facilities are less likely to seek treatment. Without accounting for this, you are likely to predict higher levels of risk around facilities.