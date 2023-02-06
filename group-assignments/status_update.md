## Water Group ## 


#### Project Proposal ####
* **Title:** After the Fire, the Rain: How fire and flood risk threaten drinking water in southern California
* **Proposal:** https://github.com/aron-walker/water-group/blob/main/group-assignments/proposal.md


#### Roles ####
- **Hannah:** I will be focusing on the flood risk portion of our research. I am also responsible for uploading the latest project proposal and updates onto our group repository. 


- **Matt:** I will be focusing on mapping fire hazard severity in a few ways. I am mapping a history of fires in Los Angeles County as well as mapping fire hazard zones as defined by CalFire. I will also be researching ways to combine our data into one map.


- **Aron:**


- **Charlotte:** I am responsible for mapping socioeconomic vulnerability and adaptive capacity factors that put certain populations in LA County at disproportionate risk before, during and after disaster events. We plan to use this data for our statistical analysis, hopefully showing how disaster risk is distributed by different socioeconomic factors.


#### Status Update ####
- **General mood:**
	- We are really excited about our decision to map multiple disaster events since we specifically chose them for their relevance to climate change, to our interests, and to each other. It will be really cool to see how it all comes together to inform our understanding of future climate risk and equitable planning. We all have been enjoying having ownership of our individual layers and figuring out how to best collect and display each aspect. We are very much looking forward to merging our data together (hopefully cleanly and beautifully) and seeing what relationships manifest.


- **What is working:**
	- Our team is effective at communicating our individual progress and seeking help from each other. We have set up the research question such that the division of labor can be evenly distributed. 
	- We have set up a system for writing code in a similar manner, making it easier for us to help each other and easier for us to combine aspects of our code further down the line.
	- We have figured out ways to effectively collaborate and accommodate each of our schedules/workloads
	- We have identified individual strengths, levels of coding, and areas of interest/development that we are all trying to be mindful of in how we divide tasks so we each get the most out of the project.
	- We get along well and it’s been a pleasure working with each other!


- **What is NOT working:** 
	- Because we have chosen to map four different environmental factors, each complex in itself, I think it’s been difficult for us to nail down exactly what risks we’re trying to convey and what data sets are best for our purposes. It feels like it’s been somewhat of a moving target.
	- An aspect of our project that excites us is how we will be able to visually show how different disaster events interact, such as how wildfires impact flooding and drinking water supplies. Figuring out how and what to map for the drinking water portion has been a challenge…we’re still not sure if we got it right and are mapping the appropriate components.


#### Data Update ####
- We are pretty much set for data, with a little finetuning to make sure we have all the fields we need for our statistics.
Fire: As far as fire, I have the data that I need. There are a few raster datasets that I found that offer more insight, and I will explore working with those in python this week. But for now, these offer a significant amount of information regarding fire history and vulnerability in LA County.
https://egis-lacounty.hub.arcgis.com/datasets/19448753fba44fac8c0443887e76078a_0/explore?location=34.085274%2C-118.224608%2C8.77
https://osfm.fire.ca.gov/divisions/community-wildfire-preparedness-and-mitigation/wildfire-preparedness/fire-hazard-severity-zones/fire-hazard-severity-zones-map/


- Floods: I have the datasets I need. I am working on how to merge the dataframes together in order to produce relevant statistics.
Special flood risk hazard areas in LA County: https://www.arcgis.com/home/item.html?id=323d8ac19ba349db80135f26225396d2
LA County Neighborhood boundary data from LA Times https://usc.data.socrata.com/dataset/Los-Angeles-Neighborhood-Map/r8qd-yxsr 
Drinking Water:
Social Vulnerability: Los Angeles County CVA Social Vulnerability Index https://geohub.lacity.org/maps/lacounty::los-angeles-county-cva-social-vulnerability-index and additional data from CalEnviroScreen (ie hazardous waste sites, pollution burden, etc). https://oehha.ca.gov/calenviroscreen/maps-data/download-data


#### Concerns ####
- **Major Concerns:**
	- We want to generate relevant statistics related to our research but we do not know what to produce as of yet. Possible ideas include identifying which vulnerability indicators are more closely related to wildfire and flood hazards.
	
	- We’re also concerned about the process of merging our data and making it look clean and pretty before our presentation next Monday. We are just unsure of how much time this may take us so we’re hoping to allocate most of this coming week…which is looking especially busy for all of us.

- **Minor Concerns:**
	- For our finished product to be truly interactive and informative, we want to be able to display pop-up windows with information on the risk profile of each census. None of us know how to code this yet, but with our combined expertise and googling skills we feel confident we can figure this out.

  - We are still unsure of what our data looks like altogether and whether or not we’ll have relevant and interesting output…we’re only slightly concerned that the different layers may not really overlap and interact in substantive ways. This may be a product of our geographic location and scope…LA County is not necessarily known to have much overlap of these events (compared to other counties) and may be too small of scope (compared to the state level) to yield meaningful results.

