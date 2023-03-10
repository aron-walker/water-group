# water-group
UP 221 Group Project Proposal

## After the Fire, Comes the Flood: Identifying Who is Flood Vulnerable After Wildfire
By: Matthew Aijala, Hannah Chun, Charlotte Sofranek, Aron Walker

#### Introduction and Motivation
In much of California, climate-related disaster risk is on the rise. Wildfires and flooding pose major risks as temperatures rise, the drought worsens, and storms become more extreme and unpredictable. In the last decade, California has focused much of its planning and policy on quantifying climate-related risks and creating potential strategies for mitigation and resilience. As a result, wildfire and flooding risk is well-documented at the state level and many larger counties, such as Los Angeles, quantify risk at the local level as well (OurCounty, 2021). However, less is known about how these climate disasters interact and likely exacerbate risks, which is especially relevant for a state like California that regularly experiences both. 

The literature shows that wildfires significantly increase the risk of flooding for up to five years, until vegetation is restored. In California, the risk is likely even greater and more prolonged since frequent wildfires create overlapping burn areas, year after year. Wildfires transform terrain and ground conditions, leaving behind a charred, barren and impermeable landscape. Normally, vegetation absorbs rainfall and reduces runoff. However, after wildfires, flooding and flood damage are often more severe as water is not absorbed and quickly flows downstream, picking up debris, ash, soil, and sediment along the way. These conditions create additional risk for flash flooding and damaging debris flows along wildfire prone areas as well as areas downstream of burned hydrologic basins and drainage networks (FEMA & National Flood Insurance Program).

Since we are UCLA Luskin planners-in-training, equity is a central tenet of our project. We know that disasters do not impact everyone equally. Certain communities are impacted more than others and recover at different rates due to a combination of well-known social risk and protective factors, such as language isolation, education, income, mobility, disability status, age, race, and many more (OurCounty, 2021). By mapping how social vulnerabilities overlap with wildfire and exacerbated flood risk, our team hopes to create a useful tool that planners and policy-makers can use to identify high risk areas and vulnerable populations that should be targeted for climate resilience planning and emergency response efforts.

#### Spatial and Temporal Scope
Our spatial scope is Los Angeles County and our temporal scope is the present, mindful that risks we identify will likely increase in the future as the Earth warms, increasing the frequency of wildfires (Halofsky et al., 2020), and the potential severity of post-fire storms (Dettinger, 2011). We selected Los Angeles County as the proper spatial scope because it is sufficiently large to embrace a variety of fire risks, flood potentials, and distribution of social vulnerabilities while also being sufficiently small to draw each type of data from a single source. We selected LA County specifically because of the increasing risk of climate-related disasters such as wildfires and flooding in the area, as well as the large population with known socioeconomic disparities (OurCounty, 2021). Many other counties face similar risks and future work might scale our methods across California or even other western states.

#### Data
We plan to incorporate four categories of data into our exploration.

- Wildfire hazard (Matt)
  - https://frap.fire.ca.gov/mapping/gis-data/ This list of datasets provided by CalFire contain one of particular interest: The Fire Hazard Severity Zones that      - demonstrate areas that are the most vulnerable to wildfires. 
  -
https://gis-calema.opendata.arcgis.com/maps/CalEMA::usgs-preliminary-hazard-assessment-2020/about
This dataset examines post fire debris zones that show areas that are most susceptible to erosion after flooding impacts an area previously impacted by fire. By combining this dataset with flooding datasets, it becomes possible to easily identify hazard zones.

- Flood hazard (Hannah) 
  - Los Angeles County???s Flood Zone Determination: https://apps.gis.lacounty.gov/dpw/m/?viewer=floodzone)
  - Los Angeles County's Special Flood Hazard Areas: https://geohub.lacity.org/datasets/lahub::special-flood-hazard-areas/explore?location=34.109204%2C-118.271744%2C10.70 

- Water systems (Aron) in California are mapped by the California Water Boards [(link)](https://gis.data.ca.gov/datasets/fbba842bf134497c9d611ad506ec48cc/explore) and watersheds are mapped globally by Hydrosheds [(link)](https://www.hydrosheds.org/). For all of California, each watershed component is mapped by California Water Boards and tagged with ???Beneficial Uses??? that include whether it is tapped for Municipal and Domestic Supply [(link)](https://gispublic.waterboards.ca.gov/portal/apps/webappviewer/index.html?id=116f7daa9c4d4103afda1257be82eb16). For LA County, the Luskin Center for Innovation joined system boundaries with additional information such as water source and system governance ([visualizer](https://innovation.luskin.ucla.edu/los-angeles-county-water-governance-mapping-tool/), [data link](https://github.com/LCIWaterProjects/Water-System-Data)). 

 Social Vulnerability (Charlotte) 
- [LA County CVA Social Vulnerability Index (SVI)]](https://geohub.lacity.org/search?collection=Dataset&q=social%20vulnerability)
The 2021 Los Angeles County Climate Vulnerability Assessment identified and incorporated 29 social vulnerability indicators to create a social vulnerability index (SVI) specific for LA County. SVI was developed with the goal of helping public health officials and emergency response planners identify and map priority communities that will most likely need support before, during, and after climate-related disasters.

#### Output Scope
Our first project objective is to identify hydrologic basins and drainage networks that spatially overlap with areas of substantial wildfire risk. To do this, we will map fire-prone areas of land, determine which hydrologic basins may be impacted, and then which drainage networks are likely to experience increased water and debris flows as a result. Once we have identified upstream areas at risk of wildfire-enhanced discharge, we will combine with a map of current flood risk to identify downstream areas at heightened risk of wildfire-enhanced flooding. Finally, we will combine these risk maps with a map of social vulnerabilities to identify the populations at greatest risk of this specific risk. As a product, we hope to produce an interactive tool, or series of maps, that will help planners and policymakers effectively and equitably target climate resilience and emergency response efforts before, during, and after wildfire and flooding events.

#### Conclusion
We plan to explore the potential threat of wildfires and exacerbated flooding in Los Angeles County using data on wildfire risk, flooding, hydrologic basins and drainage networks, and social vulnerability to identify priority areas and populations for equitable climate resilience and disaster response.

#### Works Cited
FEMA & National Flood Insurance Program. (n.d.). Flood After Fire: Your Increased Risk. FloodSmart. Retrieved February 13, 2023, from https://www.floodsmart.gov/wildfires
OurCounty. (2021). LA County Climate Vulnerability Assessment (p. 142). https://ceo.lacounty.gov/wp-content/uploads/2021/10/LA-County-Climate-Vulnerability-Assessment-1.pdf
