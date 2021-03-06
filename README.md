# Citibike-Analysis

## Summary
For this analysis take in a random set of Citi Bike data from New York city and visualize it using the tool Tableau. This is an analysis of very large datasets in which the files are not uploadable to Github. Use a jupyter notebook on a local computer in order to clean the data and randomize it for easier accesability when using the tool Tableau. In the future certainly use a big data tool such as google Colabs in order to clean datasets such as the ones in this analysis so that it is easier to upload.

## Data Cleaning and Randomization

Firstly, the analysis started by condensing the data sets of six months of data by selecting around ten percent of each months' original dataset and then joining them together at a common variable.

![Clean Data](./screen/citi_sample.png?raw=true "Clean Data")

![Join Data](./screen/six_join.png?raw=true "Join Data")

## Data Export and Tableau

![export](./screen/export.png?raw=true "export")

Lastly, using the exported csv of the joined and randomized dataset, the analysis using Tablaeu could begin. The analysis of the Citi Bike data set out ot answer three specific questions.

* How did Citi Bike usage differ between the genders as it pertains to subscription status, trip duration, and age?

* How did Citi bike usage change with the seasons?

* Where are the most used Citi Bike stations in New York City? (Least used?)

[Here](https://public.tableau.com/profile/michael.neustadter#!/vizhome/CitiBikeChallenge_16047901573030/Story1) A Tableau story was created in order to neatly visualize the analysis as well as put all of the questions next to the data visualiztions that answer them.