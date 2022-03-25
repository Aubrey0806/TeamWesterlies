# TeamWesterlies
Team Westerlies: Abbotsford flooding risks analysis
## Team members: 
Lingxuan Fan, Xilin Wan, Lan Qing Zhao 
## Introduction to the Web App:
Due to climate change, the precipitation level in B.C. has been increasing in past years. This has resulted in multiple flooding events alongside of the Fraser river, and increasing the threat to populations who live there. Just in the past year in 2021, the city of Abbotsford has experienced the largest flooding event in decades, causing about $2 billion dollars in damages and leaving many injuries. Therefore, it is important for the home owners to know the risk levels of their home to future flooding events in Abbotsford, and how to safely evacuate during a flood. Furthermore, the officials will need to know the risk levels as well for developing a more sustainable city development plan. 
## Mission Statement: 
Flooding refers to overflowing of water onto land that is normally dry due to heavy rains, sea level rises, snow melts and dams break (Alberta Water Portal Society, 2014). Floods are extremely destructive and will cause extreme physical damage to plants, animals, and communities. Furthermore,  floods can carry contaminants and viruses travel a long distance which might threaten drinking water safety. According to previous studies,  global warming effect lead to snowpack to melt and swell which increases the precipitation level and chances of floods.

Faster River basin located in B.C. is one of the largest river basins in Western Canada. The average temperature of Fraser River is 11°C, and the average monthly precipitation is around 66.5 mm (Timeanddate.com, 2021). The ongoing climate change have significantly increase the precipitation level in B.C. which result in higher frequency of flooding along Fraser River. 
Abbotsford experienced catastrophic flooding due to a heavy precipitation of 500mm in November, 2021. As a result, nearly 15,000 people were forced to leave their home, major roads and bridges were washed away, and farms were flooded with water up to two meters deep. Furthermore, the following landslides killed at least five people. Financial losses were estimated at $450 million includes 600,000 chickens and 12,000 pigs died (Weber, 2022).

The mission of our project is to we create a story map to illustrate the high risk of flooding area in Abbotsford and educate the target audience about the emergency response plan of flooding. Team Westerlies aims to support the local community’ sustainable developing by increasing the resilience to floods of residents through our storymap. Also, the web app allows user to plan evacuation routes and check the nearby emergency responders such as hospitals before the floods which can significantly reduce casualty and economic loss.
## App description and features:
Thie Web App is designed to perform flood risk analysis in the city of Abbotsford in B.C. The App provides a "level index" showing areas in Abbotsford that are at risk to future flooding events, ranking them from the lowest level flooding risk "level 1" to the highest flooding risk "level 3". On the map, areas within Abbotsford city that don't have colours overlaid have very low risks of floods, therefore are considered as safe areas in this app.

There are three features included in this app: directions, analysis and near me. With the help of these three features, the users can enhance their using experience and obtain more information, such as where and how to evacuate during a flood. 

Here are the detailed description of each feature: 

### Directions ![image](https://user-images.githubusercontent.com/100981881/160197963-fb884f90-b315-4589-a943-860af739f271.png)
- This feature allows users to find the best route between two points on the map. Users can also input locations by using their current location or entering addresses. 

### Analysis ![image](https://user-images.githubusercontent.com/100981881/160198557-ce6e67f2-d096-477d-b971-a7f272c9633e.png)
- This feature contains two sub-functions allowing users to perform more analysis based on their needs. 
- The first function is "buffer", users can create buffers around the area of their interests, for instance, distance buffer around the hospital or the evacuation centres. 
- The second function is "drive-time areas" which allows users to create an area around their point of interests with a real-life driving time, for example 5 mins/10 mins.

### Near me ![image](https://user-images.githubusercontent.com/100981881/160198808-f1834e74-aae3-410b-b70f-cc49019207db.png)
- This feature can assist users to find the near-by evacuation centres by pinning a point on map or using their current locations. This feature can also provide the fastest travel route from the user's location to the nearby evacuation centres. 

## Method and Calculation:
- **The Analytic Hierarchy Process (AHP)** is an approach that allows criteria weight estimation relying on the experts’ view of the relative importance of criteria against another for flooding (Dash and Sar, 2020). We adopted the experts’s scoring for criteria weights from previous study.

     |    Parameter   |      Landuse      |  Slope |  Elevation
     |----------|-------------|------|------|
     | Landuse |      1     |  1/3 |  0.2
     | Slope |      3     |  1 |  0.2
     | Elevation |      5     |  5 |  1

     Table 1. _Weight matrix for analytical hierarchy process_
     
- **Multi-criteria evaluation (MCE)** focuses on combining the information from several criteria based on their weights to form a single index of output.We have reclassified all the parameters that we considered for flood risk mapping and assigned rating and weights based on previous study and AHP above.
          ![image](https://user-images.githubusercontent.com/100981881/160201154-728b70fb-5b60-41c3-af39-6e921938111f.png)
          Table 2. _Classes of criteria and corresponding weights used for mapping_
          (# 重做表格或resize image）
  
- **Software:** Arcmap desktop 10.8 is used to perform data processing, AHP and MCE analysis. ArcGIS online is used to create the web app and story map. Procreate is used for logo design.

## Data Sets
     |    Data Source   |      Data files      |  Data Format
     |----------|-------------|------|
     |  City of Abbotsford Open Data |  City boundary |  Shapefile 
     |    BC Open Data Catalogue   |      Digital Elevation Model      |  Raster file 
     |    City of Abbotsford Open Data   |      Population data     |  Shapefile 
     |    City of Abbotsford Open Data   |      Hospital data      |  Shapefile
     |    Agriculture and Agri-Canada   |      B.C. land use data      |  Raster file
     |    BC Open Data Catalogue   |      Coastal water and river     |  Shapefile 
     |    City of Abbotsford Open Data   |      Abbostford community planning data      |  Shapefile
     
   Table 3. _Datasource and Metadata_
   
## References
Dash, & Sar, J. (2020). Identification and validation of potential flood hazard area using GIS‐based multi‐criteria analysis and satellite data‐derived water index. Journal of Flood Risk Management, 13(3), n/a–n/a. https://doi.org/10.1111/jfr3.12620

Flood Preparation | City of Abbotsford. (n.d.). City of Abbotsford. https://www.abbotsford.ca/public-safety/emergency-program/flood-preparation

Home | City of Abbotsford. (n.d.). City of Abbotsford. https://www.abbotsford.ca/
Pearson, C. (2018, May 13). Defining usability - Prototypr. Medium. https://blog.prototypr.io/defining-usability-e7bf42e8abd0

The Canadian Press, & Weber, B. (2022, February 16). Climate change made B.C. floods at least twice as likely, Environment Canada study suggests. British Columbia. https://bc.ctvnews.ca/climate-change-made-b-c-floods-at-least-twice-as-likely-environment-canada-study-suggests-1.5784287

WaterPortal (n.d.). Alberta WaterPortal | Environmental Impacts of Flooding. Alberta Water Portal Society. https://albertawater.com/what-are-the-consequences-of-flooding/environmental/

10 Usability Heuristics for User Interface Design. (n.d.). Nielsen Norman Group. https://www.nngroup.com/articles/ten-usability-heuristics/

## Images Reference
Azpiri, J. (2021, November 18). B.C. Flooding. Global News. https://globalnews.ca/news/8380118/b-c-flooding-abbotsford-rescue-by-water-air-heavy-flooding/
Chandra, C. (2021, November 20). This Map Shows How Climate Change Could Flood Areas Across BC’s Lower Mainland. 604 Now. https://604now.com/climate-change-flood-map-vancouver-lower-mainland-bc-2021/

Frontline-editor. (2020, January 6). Industrial Markets to Watch: West Abbotsford. Frontline Real Estate Services LTD. https://flre.ca/insights/industrial-markets-to-watch-west-abbotsford/

Hopes, V. (2021a, November 6). City of Abbotsford to implement COVID-19 vaccination policy for staff. Mission City Record. https://www.missioncityrecord.com/news/city-of-abbotsford-to-implement-covid-19-vaccination-policy-for-staff/

Hopes, V. (2021b, November 16). Woman on flight into Abbotsford captures aerial photos of flood devastation. Hope Standard. https://www.hopestandard.com/news/woman-on-flight-into-abbotsford-captures-aerial-photos-of-flood-devastation/

     






