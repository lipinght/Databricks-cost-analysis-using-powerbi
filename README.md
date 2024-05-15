# Databricks Cost Analysis using Power BI Template
Cost control and cross charge with power bi template on top of Databricks system tables

## How to make the most out of this template
System tables reflect the spending on the compute cluster level. Setting up standard tags for compute clusters through compute policies according to organizational needs is a pivotal part of the successful implementation of this template. The tags used in the compute clusters will show up in the custom_tags field of the usage table. The example in this blog is set up with the below tags: BU, owner, criticality, env, app. We recommend designing custom policies and setting up mandated tags that can help with better drill-down and cross-charging. 

## Prerequisites
* Power BI
* System tables enabled (and access granted)
* A Databricks SQL Warehouse
* Tags (for detailed drill-down analysis)


## How to set up
1. Download .PBIT (Power BI template) from github
2. Populate the parameters in Power BI template using the connection string from a SQL warehouse
3. Publish to Power BI Service
4. Start cost analysis and cross
5. (Customize if applicable)
   
### Youtube Tutorial on Setup
[![How to set up](https://img.youtube.com/vi/tTbngPbldzY/0.jpg)](https://www.youtube.com/watch?v=tTbngPbldzY)

### Youtube Tutorial on Report Navigation
💡 How to set up lookup tables
💡 How to do root cause analysis
💡 How to productionize the template
[![How to navigate report](https://img.youtube.com/vi/sF8JaF8l4Lg/0.jpg)](https://www.youtube.com/watch?v=sF8JaF8l4Lg)

### Youtube Tutorial on Customization
💡 How to do multi-tag analysis
💡 How to identify key influencers
[![How to customize](https://img.youtube.com/vi/FCtE5R1irbU/0.jpg)](https://www.youtube.com/watch?v=FCtE5R1irbU)


## Roadmap Items
* Expand the list of available KPIs in the semantic model. Add calculations like YTD and MTD DBUs and $DBUs
* Remove the need for any manually imputed reference data, as the system tables evolve 
* Capture price changes and reflect those historically 
* Track the progress against any existing commercial agreements


