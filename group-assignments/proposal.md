## After the Fire, the Rain: How fire and flood risk threaten drinking water in southern California

#### Introduction and Motivation
In much of California, water is a scarce commodity. While much political and popular discourse focuses on water sufficiency, California’s precious water supplies also face diverse quality threats, from overdraft exacerbating arsenic pollution (R. Smith et al., 2018) to rising coastal water tables (Befus et al., 2020). These threats impact a problematically fragmented assemblage of public and private water systems (Mullin, 2020) that already deliver water with significant inequalities in quality (Pace et al., 2022). We are interested in exploring the impact of two coupled threats on these water systems – wildfires and post-fire floods. Wildfires transform regular vegetation into a toxic mixture of soluble metal ions and nitrates that subsequent winter storms flush into water systems (H. G. Smith et al., 2011), causing spikes in water pollution (Emmerton et al., 2020). While these impacts from past fires have been studied at basin-scale across the western United States (Rust et al., 2018), we propose zooming into a specific county to explore how areas prone to post-fire flooding intersect with surface and near-surface sources of drinking water. This intersection of wildfire and water supply has been identified as a key research priority (Pierce et al., 2021). Identifying communities reliant on surface and near-surface water supplies whose quality might be compromised by post-first flooding might prioritize specifically vulnerable locations for climate resilience investments in the form of enhanced water treatment systems and/or supply redundancy by linking to nearby systems.

#### Spatial and Temporal Scope
Our spatial scope is (xyz county) and our temporal scope is the present, mindful that risks we identify will likely increase in the future as Earth warms, increasing the frequency of wildfires (Halofsky et al., 2020), and the potential severity of post-fire storms (Dettinger, 2011). We selected a county as the proper spatial scope because it is sufficiently large to embrace a variety of fire risks, flood potentials, and water sources, while also being sufficiently small to draw each type of data from a single source. We selected (xyz county) specifically because (reasons). Many other counties face similar risks and future work might scale our methods across California or even other western states.

#### Data
We plan to incorporate four categories of data into our exploration.

- Wildfire hazard (Matt)
  - https://frap.fire.ca.gov/mapping/gis-data/ This list of datasets provided by CalFire contain one of particular interest: The Fire Hazard Severity Zones that      - demonstrate areas that are the most vulnerable to wildfires. 
  - https://gis-calema.opendata.arcgis.com/maps/CalEMA::usgs-preliminary-hazard-assessment-2020/about
This dataset examines post fire debris zones that show areas that are most susceptible to erosion after flooding impacts an area previously impacted by fire. By combining this dataset with flooding datasets, it becomes possible to easily identify hazard zones.

- Flood hazard (Hannah) 
  - Los Angeles County’s Flood Zone Determination: https://apps.gis.lacounty.gov/dpw/m/?viewer=floodzone)
  - Los Angeles County's Special Flood Hazard Areas: https://geohub.lacity.org/datasets/lahub::special-flood-hazard-areas/explore?location=34.109204%2C-118.271744%2C10.70 

- Water systems (Aron) in California are mapped by the California Water Boards [(link)](https://gis.data.ca.gov/datasets/fbba842bf134497c9d611ad506ec48cc/explore) and watersheds are mapped globally by Hydrosheds [(link)](https://www.hydrosheds.org/). For all of California, each watershed component is mapped by California Water Boards and tagged with “Beneficial Uses” that include whether it is tapped for Municipal and Domestic Supply [(link)](https://gispublic.waterboards.ca.gov/portal/apps/webappviewer/index.html?id=116f7daa9c4d4103afda1257be82eb16). For LA County, the Luskin Center for Innovation joined system boundaries with additional information such as water source and system governance ([visualizer](https://innovation.luskin.ucla.edu/los-angeles-county-water-governance-mapping-tool/), [data link](https://github.com/LCIWaterProjects/Water-System-Data)). If we want to pivot to looking at historical impact from past first, we could use data from the California State Water Resources Control Board on surface water quality [(link)](https://data.ca.gov/dataset/surface-water-toxicity-results) and the Surface Water Ambient Monitoring Program [(link)](https://data.ca.gov/dataset/surface-water-ambient-monitoring-program).

 Social vulnerability (Charlotte) 
- [CDC/ADSTR Social Vulnerability Index (SVI) Data – 2020 California County](https://www.atsdr.cdc.gov/placeandhealth/svi/data_documentation_download.html)
The CDC and ADSTR created the SVI to measure the relative vulnerability of every census tract/county in the United States based on 15 social factors (including unemployment, minority status, disability, etc) grouped into four general themes (SES, household composition & disability, minority status & language, housing type & transportation) all of which are ranked for every tract/county, in addition to an overall ranking. SVI was developed with the goal of helping public health officials and emergency response planners identify and map priority communities that will most likely need support before, during, and after a hazardous event (such as wildfire, flooding, landslides, water contamination).
 - [CalEnviroScreen(air pollution burden)](https://oehha.ca.gov/calenviroscreen/maps-data)
 - [Healthy Places Index(community level)](https://www.healthyplacesindex.org/)
 - [Area Deprivation Index (ADI) by HRSA](https://www.neighborhoodatlas.medicine.wisc.edu/)
 - [2020 Homeless counts and densities in LA county at the community level](https://geohub.lacity.org/datasets/lacounty::homeless-counts-2020/about)
- It is important to note that point-in-time homeless counts are notoriously and historically inaccurate due to the dynamic nature of homeless populations and the fact that many are difficult to reach. [By-name data](https://community.solutions/quality-by-name-data/), such that Built for Zero is pioneering, will be key for more effective public health and planning initiatives. Additionally, we have chosen to use 2020 data as LAHSA did not conduct the count in 2021 due to Covid-19 and the 2022 Count data has some [documented and notable holes](https://www.latimes.com/california/story/2022-09-24/doubts-raised-over-the-los-angeles-homeless-count-is-it-time-for-a-new-way).  
#### Output Scope
Our first project objective is to identify public water systems whose supply areas (upstream watersheds) spatially overlap with areas with substantial wildfire risk. To do this, we will map fire-prone areas of land, determine which hydrologic basins these areas feed, and then which water systems draw from these basins. Once we have identified these systems, we will identify how their customers overlap with socially vulnerable populations, to identify the highest priority water systems to target for enhanced resilience. As products, this looks like two maps, perhaps with close-up visualizations of the most impacted water system areas, as well as lists and charts comparing affected populations and their characteristics.

#### Conclusion
We plan to explore the potential threat of wildfires on drinking water systems in (xyz county) using data on wildfire risk, flooding/hydrology, public water systems, and social vulnerability to prioritize public water systems for targeting climate resilience upgrades to ensure equitable provision of high quality water in a warming world.

#### Works Cited
Befus, K. M., Barnard, P. L., Hoover, D. J., Finzi Hart, J. A., & Voss, C. I. (2020). Increasing threat of coastal groundwater hazards from sea-level rise in California. Nature Climate Change, 10(10), Article 10. https://doi.org/10.1038/s41558-020-0874-1

Dettinger, M. (2011). Climate Change, Atmospheric Rivers, and Floods in California – A Multimodel Analysis of Storm Frequency and Magnitude Changes1. JAWRA Journal of the American Water Resources Association, 47(3), 514–523. https://doi.org/10.1111/j.1752-1688.2011.00546.x

Emmerton, C. A., Cooke, C. A., Hustins, S., Silins, U., Emelko, M. B., Lewis, T., Kruk, M. K., Taube, N., Zhu, D., Jackson, B., Stone, M., Kerr, J. G., & Orwin, J. F. (2020). Severe western Canadian wildfire affects water quality even at large basin scales. Water Research, 183, 116071. https://doi.org/10.1016/j.watres.2020.116071

Halofsky, J. E., Peterson, D. L., & Harvey, B. J. (2020). Changing wildfire, changing forests: The effects of climate change on fire regimes and vegetation in the Pacific Northwest, USA. Fire Ecology, 16(1), 4. https://doi.org/10.1186/s42408-019-0062-8

Mullin, M. (2020). The effects of drinking water service fragmentation on drought-related water security. Science, 368(6488), 274–277. https://doi.org/10.1126/science.aba7353

Pace, C., Balazs, C., Bangia, K., Depsky, N., Renteria, A., Morello-Frosch, R., & Cushing, L. J. (2022). Inequities in Drinking Water Quality Among Domestic Well Communities and Community Water Systems, California, 2011‒2019. American Journal of Public Health, 112(1), 88–97. https://doi.org/10.2105/AJPH.2021.306561

Rust, A. J., Hogue, T. S., Saxe, S., McCray, J., Rust, A. J., Hogue, T. S., Saxe, S., & McCray, J. (2018). Post-fire water-quality response in the western United States. International Journal of Wildland Fire, 27(3), 203–216. https://doi.org/10.1071/WF17115

Smith, H. G., Sheridan, G. J., Lane, P. N. J., Nyman, P., & Haydon, S. (2011). Wildfire effects on water quality in forest catchments: A review with implications for water supply. Journal of Hydrology, 396(1), 170–192. https://doi.org/10.1016/j.jhydrol.2010.10.043

Smith, R., Knight, R., & Fendorf, S. (2018). Overpumping leads to California groundwater arsenic threat. Nature Communications, 9(1), 2089. https://doi.org/10.1038/s41467-018-04475-3

