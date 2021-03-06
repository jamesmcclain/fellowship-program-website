---
published: true # change to true once ready to post

title: "Foot Steps of Rome: Calculating the Cost of Travel in the Roman Empire" # project title inside quotes
excerpt: "Calculate the cost of traveling between ancient Roman population centers" # shows on project list page

# project attributes
requirements: # bullet list of requirements – one requirement per line – follow below format
 - "Familiarity with Python"
 - "At least a basic understanding of GIS concepts"
 - "Knowledge of Scala and Roman history not required but helpful"
tags: # one tag per line – spaces are allowed in tags – follow below format
 - "Geospatial analysis"
 - "python"
difficulty: "Medium" # easy, medium, hard – pick one
mentors: # github username without the @ – example: designmatty
 - "jbouffard"
 - "moradology"

# This file uses Kramdown. See https://kramdown.gettalong.org/syntax.html for syntax
---

This project seeks to use [GeoPySpark](https:///github.com/locationtech-labs/geopyspark), a Python library
for analyzing geospatial data, to produce novel datasets which can be used by archaeologists, classicists, and
historians. Initial work will include calculation of tobler cost-rasters for a better understanding the
cost of travel in the Roman Empire. Ideally, this project would produce multi-modal cost-surfaces which include
information about ports and knowledge derived from reconstruction of technologies from the era.

## Milestones

#### Preparation

In the beginning of the project you will prepare by:

- Become familiar with the GeoPySpark codebase and its environment
- Create a roadmap

#### Coding Phase 1

In the first coding phase, you'll create a juptyer notebook using GeoPySpark to do cost distance calculations.

- Create a Tobler walking speed notebook
- Expand notebook to include cost distance calculations

#### Coding Phase 2

In the second coding phase, you'll further the analysis by determining the changes through time for cost.

- Optimize relevant processes in GeoTrellis/GPS
- Calculate cost distances at other points in time
- Determine the changes in cost between time periods

#### Coding Phase 3

In the final coding phase, you'll encorporate new data into the analysis, produce graphics, and write up your results in a blog post.

- Seek to include knowledge about ports, sea travel, and technologies from the era
- Potential branching out to draw inferences about trade
- Create a single layer that shows the differences in costs
- Produce graphics and/or interactive maps
- A blog post about the work
