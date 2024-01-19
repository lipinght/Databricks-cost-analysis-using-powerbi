# Databricks Cost Analysis using Power BI template
cost control and cross charge with power bi template on top of Databricks system tables

## How to make the most out of this template
System tables reflect the spending on the compute cluster level. Setting up standard tags for compute clusters through compute policies according to organizational needs is a pivotal part of the successful implementation of this template. The tags used in the compute clusters will show up in the custom_tags field of the usage table. The example in this blog is set up with the below tags: BU, owner, criticality, env, app. We recommend designing custom policies and setting up mandated tags that can help with better drill-down and cross-charging. 

