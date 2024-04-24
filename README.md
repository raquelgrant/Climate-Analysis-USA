# Climate Analysis USA

This repository draws on analyzing temperature changes throughout the seasons in the continental United States using information from The Washington Post's "2°C: Beyond the Limit." All temperatures are represented in Fahrenheit. 
 
### Where did the contents of this repository come from?

- This data was retrieved from a *Washington Post* repository for a study done using the National Oceanic and Atmospheric Administration's Climate Divisional Database (colloquially, nClimDiv). The study was performed in 2018 and then refined in 2019.
   > This was accessed through another *GitHub* page that can be found [here](https://github.com/washingtonpost/data-2C-beyond-the-limit-usa).
- The original repository also contained temperature change data for specific counties in the states and national yearly temperature averages from 1895 to 2019.
- Using *Google Colaboratory* (a notebook service used for simple coding), I filtered the original dataset into a smaller more specific set of information. 

### What *are* the contents of this repository?

-  A CSV file of the original dataset displaying the temperature changes through all 4 seasons, the maximum warming season, the annual temperature changes, and the states represented
-  A CSV file of my filtered data set only displaying the winter and annual temperature changes with their respective states
- The Python notebook I created for replication that specifically describes the steps I took to create the new subset of data  
- The two choropleth maps I created to visualize the data

## Visualizations

Since the subset displayed both winter temperature changes and annual temperature changes, I thought it would be best to create two seperate visualizations for them. 

>The map houses a gradient of colors to represent the differing severities of the temperature changes. The darkest blues have the lowest levels of temperature changes, then the sort of middling changes are a tan shade, with the most extreme changes being darker reds.

<noscript><img src="https://datawrapper.dwcdn.net/EWX4t/full.png" alt="" /></noscript></div>


>*While this is only an image of the map, you can visit the map on [Datawrapper](https://www.datawrapper.de/_/EWX4t/) for an interactive version. This will allow you to roll over the states to see their names and exact temperature changes.*

<noscript><img src="https://datawrapper.dwcdn.net/XBE66/full.png" alt="" /></noscript></div>

>*Again, this is the image version of the map. The interactive version can be found at this [Datawrapper Link](https://www.datawrapper.de/_/XBE66/).*


### What can I do with it?

The data found in this repository can help guide further studies into climate change in the continental United States. Analyzing which areas of the country have the greatest increase in temperature, even if by just a fraction of degree, can be incredibly impactful. These analysises can help target causes and possibly discover solutions.

### How do I get started?

Navigate to the *ProcessNotebook.ipynb* tab in order to get directions on how to recreate this process. 
#### This repository was created by Raquel Grant for usage in Professor Gotzler's English Class at the University of North Carolina at Chapel Hill. 
