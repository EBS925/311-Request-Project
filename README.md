# 311-Request-Project

Dat512 

Canisius College

Kyle Eberle
# Project Description
In this project I was tasked with looking into the public Buffalo 311 Request data, along with any comparitive data,
to analyze for general trends or comparisons with the data sets.
I decided to look at both the open 311 Request data and the Crime Incident data, focused on the entire 2022 year.

In this analysis I focused on the following:
* General cleanup and manipulation of the data sets
  * To be able answer questions with the most compelling visuals
* Looking at the most common occurences in each data set
  * Request Reasons for the 311 data, Incident Type for the Crime data
* Types of crimes and their trends over specific days of the week
* Geo-Map visuals shocasing the breakout of requests/crimes by the Buffalo Neighborhoods
# Data used for project
https://data.buffalony.gov/Quality-of-Life/311-Service-Requests/whkc-e5vr

https://data.buffalony.gov/Public-Safety/Crime-Incidents/d6g9-xbgu
# Project Overview
#### Data Pull/Cleaning
* Data was pulled from the Open Buffalo Data site using API request method
* Cleansing checks on NA counts was performed, NAs cleaned up where necessary
* Addtional cleansing of datetime conversions 
* Creating subsets of only essential columns/grouping reasons & types of lesser occurences
#### Early Stage Analysis
* Looked at value counts of each variable as their percentage of the whole data set
  * In the 311 Request data we saw that the majority of the data set was made up of Sanitation,
   Housing, Streets/Street Repairs
  * In the Crime Incident data we saw that over 40% was made up of Thefts, while the other
   major crimes were Breaking & Entering, and Assault
* Dug into the breakout of Crime Type over each day of the week
  * On the Theft category we see consistent rates across the days, except on Sunday where
   there is a decent dip in the overall crime rate for theft
#### Main Comparison Visual - Geo-Map Density Plot
In this analysis I had the theory that areas of Buffalo would have simalar rates of 311 requests to crime rates

![alt text](https://github.com/EBS925/311-Request-Project/blob/main/311%20Map.jpg?raw=true)

When I looked into the map of 311 Requests I found that the highest concentration of requests were in the Elmwood/Bidwell
area and the Bailey Avenue/Cheektowaga areas. This tracked with what i expected to see, especially with the Elmwood/Bidwell 
neighborhood. When I used to live on Lexington Ave in Elmwood, I remember an abundance of Street Repairs, Sanitation/Sewage work,
Tree Maintanince always being worked on. Also from my time being in that area I remember always hearing about numerous petty thefts and crimes occuring 
around our neighborhood, and parts of Bailey Avenue unfortunately have a reputation for crimes whicjh I expected to see in my next plot

When I looked into the Crime incident data, I got a result I wouldnt say I was surprised with, but one that did contradict my original theory.
In this plot I found that the highest rates of crime over 2022 occured in Downtown Buffalo and the North Buffalo areas. Seen below we can see that breakout 
showing the high rates of theft crime throughout the areas mentioned.
