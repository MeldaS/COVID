# CASA COVID-19 Kaggle Challenge Meeting Notes

## _yyyy-mm-dd_ _meeting title_

## 2020-03-24 Kaggle COVID Meeting 1


### agenda
* Main task to address
** Non-pharmacutical interventions
* Subtasks to address
* Set up Git Repo
** keep meeting notes here
** save code chunks
** suggest models to use
* Arrange next meeting
** Friday 4:30pm

### Ideas for addressing the task

* Non-parmaceutical interventions 
** how could virus be contained at a local level
** long term behaviour change is required, what are communing flows going to look like, how to these effect transmission

* Reporting/diagnostics and surveillance
** what are the uncertainties in how the data is being reported, can this explain differences between infection trajectories?

* Rough process for identifying high risk transmission routes
1. Make a list of places based on age to identify where spread will be bad. Identify ‘places at risk’
2. Make a list of places that economically key – think about sectors. Identify economic hubs by sector.
*  retail centre definition by Liverpool (https://data.cdrc.ac.uk/dataset/retail-centre-definitions)
3. Do a gravity model to see which flows between places would link up risk populations: identify ‘risky transmission routes’
4. Get data point Hospitals their capacity. Use this to update the gravity model.
5. GWR between countries for demographic - independent variable: transmission rates, death rates, etc.

* NPL Specific
** Quantify the extent of production crossovers (a term I'm inventing). You keep hearing about how car company x/brewery y is using their factory to produce masks/ventilators/gloves. Could be interesting to do some kind of analysis (potentially text-mining of news? i'm not sure) to estimate/quantify this

* Generaly thoughts on approaching the tasks
** balance between reviewing existing literature and building our own models
** we can add value by linking to public policy, transport & flows, geodemographics
** this virus is unprecedented compared to other viruses, how useful is previous research...?


### Data
* we can add our own data sets to Kaggle, so don't need to be limited to research archives.
* Also the workbook could have some additional alanysis that we remove when submitting but publish elsewhere
* what are the geographic areas of intereest?
** start with whereever we can find most relevant data for


### skills/interests
* obi: npl clustering; urban flow; python
* melda: some text processing; economic development; remote sensing; python
* sam: playing with uncertainty of data, some figures underreported or classified differently; python
* bea: networks and percolation; community clustering; developmental aspect and link with public policy; 
* bonnie: text analysis, clustering literature; flow data communicating flow data; R
* matt: remote sensing, spatial interaction modelling; R
