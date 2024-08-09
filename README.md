# ancient_routes_paper

Introduction and References: Connected Past + Article

## Repository structure

### ./data/
The folder contains data files created from two public data sources using scripts. 
The data sources are Orbis (https://orbis.stanford.edu/) and Icrates (https://archaeologydataservice.ac.uk/archives/view/icrates_lt_2018/). 

|  data file        | source script |
|-------------------|---------------|
| MIM_site.Rdata    |   ......      |
| df_all_melted.csv |   COST & MI   |


### ./GIS/
This folder contains shapefiles to reconstruct the least-cost path networks used in the paper and a workflow document that allows others to reproduce our analysis.

|  data file        | source script |
|-------------------|---------------|
| ICRATES_Sites.shp   |  Sites filtered from Icrates dataset    |
| LCP_Network.shp |   LCP network   |
| ORBIS.shp | ORBIS geospatial network data |
| ORBIS_ShortestDistance.shp | Shortest distances between filtered sites using the ORBIS network model |


### ./src/
| script                   | purpose |
|--------------------------|---------|
| analyse_pairs-of-sites.R | |
| compare_matrices.R       | |
| create_MI_networks.R     | |
| network_of_sites.R       | |
| analyse_persistence.R    | |
| compute_coocurrence.R    | |
| create_time-slices.R     | |
| transform_MI&Cost_data.R | |
| choose_MI_cutoff.R       | |
| create_cost_network.R    | |
| network_comparison.R     | |


> put the scripts in order?
>
> 