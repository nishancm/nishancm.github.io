# Introduction

In this project, we help to explore macro level and micro level factors that potentially affect suicide rates. For the macro level analysis, we are using interactive plots to explore how suicide rates of countries evolved over the years. Also, we help to understand the dynamics between suicide rate and multiple factors such as GDP per capita, percentage enrolled in secondary education and etc. For the micro level analysis, we go into an individual level and explore different personal attributes that might lead to suicide attempts. You can play around with the visualizations and learn more about it using the following [link](https://nishancm.github.io)

# file structure

## Code 
`Code` folder contains jupiter notebooks with Python code used to generate the visualizations.
`Data_Acquisition.ipynb` - Helps to merge different data sources (e.g. suicide rates from IHME, world bank data) to output `Data/suicide.csv` file
`yearly_suicide_rates.ipynb` - Generate gap minder plots to show the relationship between suicide rates and different variables
`Generate_ForeverAlone_visualization.ipynb` - Generate a unique visualization to present data at an individual level

## Data
`Data` folder contains cleaned version of Data used to generate visualizations.
`suicide.csv` - Used with macro-level visualisations
`foreveralone.csv` - Used with micro-level visualisation
`raw_data` folder contains preliminary data files used in the process

## Final_presentation_Jose_Nishan.pdf
`Final_presentation_Jose_Nishan.pdf` contains the slides from the final presentation to the class

## index.html
`index.html` is the `html` file for the website containing javascript elements for each visualization.
