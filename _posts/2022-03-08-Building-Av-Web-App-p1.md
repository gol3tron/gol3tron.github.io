---
layout: post
title: "Building an Aviation Web App"
date: 2022-03-08
tags: aviation python
---
Hi everyone,

I've been working on my CFI rating for a little while now, and in the process of constructing lesson plans it has occured to me that it might be instructive to create some kind of a web app and/or series of companion posts that might be useful in explaining a few basic principles of flight. 

Specifically, I am envisioning creating a web-based tool that might perform a few different functions:

1. Given an aircraft type and conditions, perform takeoff/landing performance calculation (likely a common training a/c such as a 172 or cherokee/archer)
2. Using POH recommendations for certain special conditions, give the user the ability to select "modifiers" to performance calcuations (e.g. grass runways, sloping runways of specified grade, and different a/c loading conditions)
3. Create an "easy interpolator" for POH data to get performance data at specific conditions (generic such that it could be used as 1D or 2D interpolation of any type)
4. Vector visualization for true heading, true course, wind correction angle analysis as an aid to instruction 
5. Vector visualization for forces of flight, left turning tendencies
6. Other simple calculators (pressure/density altitude, true airspeed/equivalent airspeed, top of climb/descent, crosswind component)

Ultimately, I'm not a graphic designer, so the visualizations may be limited or require some kind of plugin situation. I will have to figure that one out... Fortunately, the actual calculation part is straightforward and I plan to share all calculations/code/other materials as I create them!

Stay tuned...

Tailwinds,
Adam
