# Code for the Project 


## Data Cleaning: 

We eliminated several features that don't make sense as regression variables, specifically text descriptions and links to images. We removed the following features due to personal judgments 

- Street Address: Redundancy
- Description, Number of Photos, Home Image: all relating to values we can't regress on 
- Number of Window Aesthet/ics: We could not figure out what this is referring to 
- Number of Community Features, Accessibility Features, and Window Features: all data was the same 
- Latest Price Source: Text data for broker which seems to have lots of missing data and is not connected to the primary focus of the variables we are looking at, which are economic and house features 
