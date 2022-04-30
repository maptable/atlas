# Maptable Atlas

Accessing high-resolution, timely socioeconomic data (e.g, population, employment, consumption, and wealth) of human settlements is critical. However, in many developing countries, reliable local-scale socioeconomic data remain scarce. In this project, we plan to harness the power of multiple sources of big data (e.g., satellite data, cell phone data), online communities, and machine learning algorithms to solve this problem. 

Our [previous research](https://www.pnas.org/doi/10.1073/pnas.1903064116) and [practice](https://github.com/leiii/restaurant) has revealed that big data can be a good predictor of socioeconomic attributes of locations; projects like [OpenStreetMap](https://www.openstreetmap.org/) have also demonstrated the value of open source + crowdsourcing in (global road network) data mapping. With the support of new big geo-data and AI, it is possible for us to map multidimensional socioeconomics on a global scale.


To achieve this goal, we plan to divide this task into three parts. 

- The first part is to use the online community to structure statistics for major countries around the world (the census data for China is now [complete](https://github.com/leiii/census) and a working paper is also available [here](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4049338)). 

- The second part is to build a good tool for handling spatial data, i.e., [Maptable](https://www.maptable.com), to meet the needs of data collaboration, analysis, visualization, etc. We have been developing this tool for a year and a half and have accumulated 6.5k commits on GitHub, see the online version [here](https://www.maptable.com). 

- The third part is to leverage the power of machine learning models. We will collect as much data as possible from satellite remote sensing, street view, cell phone, traffic, etc. around the world and train the models to complete the prediction work. 

The final result is to output the coordinates/geofence of a location that can quickly return a series of structured information to the user (e.g. how many people are here, how many jobs, how much GDP is generated, what is the traffic situation, housing price, etc.).

