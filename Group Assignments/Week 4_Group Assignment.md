# Mini Group Assignment

## Project Title and Link to Proposal
San Francisco: Crime and Green Space

[Proposal](https://github.com/sgdiek/Sara.Sarah/blob/main/Group%20Assignments/Project%20Proposal%20Markdown.md) 

## Roles
We plan to work through the majority of the midterm together. We think it is important for each of us to contribute to both the maps and charts.
Sara T. will do the data exploration and charts for crime. Sarah D. will do the data exploration and charts for green space. We are unsure exactly how we will split up the maps. For example, one of us will make a map for petty crimes while the other makes a map for felonies. Or, we will take a look at the top 2 most common crimes in SF and split those up between us to create maps of each. 

## Status Update
Morale is high. We work really well together. We have had an easy time scheduling meeting times each week. We have been splitting the work evenly and helping each other troubleshoot when stuck. We are both very responsive and have great communication. 

## Data Update
We still plan to explore and use the data sets that we proposed in our project proposal: [SF County Police Incident Reports](https://data.sfgov.org/Housing-and-Buildings/Land-Use/us3s-fp9q) and [SF County Land Use](https://data.sfgov.org/Housing-and-Buildings/Land-Use/us3s-fp9q). However, we are also exploring the potential to use OpenStreetMap to locate parks in our geographic area of interest (SF County). We want to make sure that we have a data source that quantifies the size of green spaces in SF County, and we still have to explore bringing in OSM data on python. If OSM is not able to provide us with the area of park spaces, we want to explore potentially merging the land use data set from the SF government and OSM data. But this is something we're currently exploring and may need help on. There's also the concern that some parks in SF county are either not accounted for in OSM, or under the category "yes," which would skew our findings. 
## Concerns
Most of our concerns have to do with our data and bringing together our different sources of data:
* After last week's lab, we did some initial exploring of green spaces in SF county using the 'leisure': ['park'] argument. The data in OSM tells us that there are 18 parks in SF County. However, this already conflicts with the number of parks that are designated in the land use data set. So, we need to reconcile these two facts and figure out how to best accurately depict the number and size of parks in SF County. 
* In our feedback on our project proposal, Bob brought up a very good point that we hadn't thought of. The fact that Census tracts might share park spaces. Since we want to do our analysis at the Census tract level, we would need to figure out a way to account for the fact that parks and green spaces might traverse more than one Census tracts. I think this is something that might be easier to address when visualized, but it's definitely a concern, and we are unsure how to exactly address it. 
* In the midterm assignment, it instructs that student presentations must include one data overlay. We believe that means that we need to bring in one additional layer of data to place on top of our intially constructed map (e.g. a map of green space in SF with data on crime rates mapped on top). However, we are not entirely sure that this accurate or how to do this in Python.
