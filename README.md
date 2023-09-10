# intel_Unnati_grand_challenge_Aventador_team

# DEPENDENCIES TO RUN CODE
1)conda env
2)matplotlib
3)scikit-learn
4)pandas
5)vs code
6)seperate-kernel

# GRAPHS 
![image](https://github.com/RaviTeja20003/intel_Unnati_grand_challenge_Aventador_team/assets/103447565/cf7f11cb-ba06-42dc-ace1-c87c43641ab4)
Role of DBSCAN Algorithm:

Clustering Alerts: The primary role of the DBSCAN algorithm is to cluster ADAS (Advanced Driver Assistance Systems) alerts based on their geographical coordinates (latitude and longitude). It groups alerts that are spatially close to each other into clusters.

Density-Based Clustering: DBSCAN is a density-based clustering algorithm, which means it forms clusters based on the density of data points in the spatial domain. It identifies areas where alerts are concentrated and considers regions with lower alert densities as noise or outliers.

Blackspot Identification: By applying DBSCAN, the algorithm identifies clusters with a high density of alerts. One of these clusters is selected as the blackspot cluster, representing an area where drivers frequently encounter situations requiring ADAS intervention.

Alerts Generated:

The alerts generated by ADAS systems can vary depending on the specific systems and sensors in use. Common types of alerts generated by ADAS systems include:

Lane Departure Warning (LDW): Alerts when the vehicle unintentionally drifts out of its lane.

Forward Collision Warning (FCW): Alerts when the vehicle is approaching another vehicle or obstacle too quickly and a collision is imminent.
Headway monitoring and Warning (HMW) : Alerts when the distance between the vechiles is less than the safe distance.

Insights:

Cluster Identification: DBSCAN helps identify clusters of alerts with a high spatial density. These clusters represent regions where drivers frequently encounter specific driving scenarios or challenges.

Blackspot Identification: The cluster with the highest density of alerts is selected as the blackspot cluster. It is an area where drivers consistently experience situations prompting ADAS alerts, potentially indicating safety concerns.

Safety Assessment: The presence of a blackspot cluster suggests the need for a safety assessment in the identified region. Safety experts can further investigate the causes of alert density and potential safety hazards in this area.

Targeted Interventions: Once blackspot regions are identified, targeted safety interventions can be planned and implemented to address specific safety challenges in those areas. These interventions may include road improvements, signage enhancements, or driver education programs.

Continuous Monitoring: Monitoring the spatial distribution of alerts and the effectiveness of safety measures in blackspot areas is essential. Continuous data collection and analysis can lead to ongoing safety improvements.

In summary, the DBSCAN algorithm helps identify and delineate areas where ADAS alerts are concentrated, allowing for the identification of potential blackspot regions. These regions can be further analyzed and addressed to improve road safety and reduce the likelihood of accidents or safety incidents.

![image](https://github.com/RaviTeja20003/intel_Unnati_grand_challenge_Aventador_team/assets/103447565/ab07dd8a-e3bf-45e2-9bd9-aa71c9540f43)
![image](https://github.com/RaviTeja20003/intel_Unnati_grand_challenge_Aventador_team/assets/103447565/35b32167-b40e-4a63-883d-3a57e112ba70)
