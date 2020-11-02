---
title: "README"
author: "Bob Erdman"
date: "September 18, 2020"
output: github_document
---
  In this project, we wanted to investigate the effect of temperature and rainfall on crop yields, for two typical agricultural
regions in the State of Georgia: Sumter county (home of Plains and peanut/cotton production), and Toombs, source of Vidalia onions.
Happily, the Univ. of GA agricultural research and climate studies faculty were able to provide weather data by county from the mid 90's 
to 2017.    For crop yield data, the USDA crop census provides a county/state breakdown for crop commodities.    
Using polynomial regression with seasonal smoothing in R, we did see a small but significant decrease in precipitation of -31 mm, while temperatures 
increased by +3.5 C.  Both of these changes accelerating around 2010 or so.   Precipition shows a peak around Aug-September season, most likely summer 
thunderstorms.
  Unfortunately, the USDA crop yield data is only reported on a 4-year basis.   We do not have a level of detail here to make a cause-effect determination
of temp vs. precip. vs yield.    Glancing at the crop yield census (not shown) for Sumter shows no dramatic decline in cotton or peanut tonnage produced.
Year-to-year data from the couny agents would be helpful here, but was not pursued further.   
  The lesson here is that data from different sources may not track together over time periods.   A quick acceleration in warming and drying after 2010 did not 
  result in a decline in yields for the last census.   Perhaps greater use of irrigation, or increases in tilled acreage may be occurring at the farm level.
  Further study is needed to prove or disprove a climate/yield relationship, and without yearly yield data, we held off on the Toombs onion analysis for now.
  



