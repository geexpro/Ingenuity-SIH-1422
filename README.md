
![Copy of INGENUITY2](https://github.com/geexpro/Ingenuity-SIH-1422/assets/88074810/de5f7993-37da-46a3-8d5c-d10e54297bc7)
<img width="1470" alt="Screenshot 2023-09-20 at 2 16 26 PM" src="https://github.com/geexpro/Ingenuity-SIH-1422/assets/88074810/7357112c-4946-47f2-9aec-95fae21bd3fd">


# Enhancing Avalanche Victim Identification: Leveraging AI/ML Technologies for Efficient Detection in Harsh Terrain


This innovative project aims to revolutionize avalanche victim identification by harnessing the power of Artificial Intelligence (AI) and Machine Learning (ML) technologies. In the unforgiving and treacherous landscapes of avalanche-prone regions, locating and identifying avalanche victims swiftly is a matter of life and death. Traditional search and rescue operations can be slow and resource-intensive, often hindered by challenging terrain and adverse weather conditions.

Our solution combines cutting-edge AI and ML algorithms with advanced sensing and image processing technologies. By leveraging this powerful synergy, we empower search and rescue teams with the ability to detect and locate avalanche victims more efficiently and accurately than ever before. Our system can analyze complex data from various sources, including aerial imagery, ground sensors, and even remote drones, to provide real-time information on victim locations.

This project aims to make a significant impact on avalanche rescue efforts, saving valuable time and increasing the chances of survival for those caught in these perilous situations. We are committed to pushing the boundaries of technology to enhance the safety and effectiveness of search and rescue operations in harsh avalanche terrain.




## Authors

- [Abhinav Saini](https://www.github.com/iabhinavsaini)
- [Aditya Berry](https://www.github.com/iabhinavsaini)
- [Tanishq Trivedi](https://www.github.com/iabhinavsaini)
- [Yashwini Singh](https://www.github.com/iabhinavsaini)
- [Ankush Singh](https://www.github.com/iabhinavsaini)
- [Vidhi Jain](https://www.github.com/iabhinavsaini)




## Idea and Approach

We are actively pursuing a comprehensive solution through the development of specialized software aimed at providing users with avalanche prediction details, thereby safeguarding them from venturing into avalanche-prone areas. Subsequently, we plan to leverage cutting-edge AI/ML algorithms to create a sophisticated system that will be deployed on autonomous Vertical Takeoff and Landing (VTOL) platforms. This system will efficiently detect and track individuals buried beneath avalanches, furnishing precise victim information. This invaluable data will enable rescue teams to execute timely and effective operations.

Our approach to this endeavor is structured into two distinct yet interconnected phases, each of which will be elaborated upon in the subsequent sections:
- Prediction Model
- Response Model


Prediction Model:

In this phase, we will focus on the development of a robust predictive model. This model will utilize a combination Ahistorical data, meteorological information, and terrain analysis to accurately forecast potential avalanche occurrences. The objective is to provide users with timely and reliable information, empowering them to make informed decisions and avoid areas at risk.


![1](https://github.com/geexpro/Ingenuity-SIH-1422/assets/88074810/80da19c0-b2f6-4117-987a-ab2235126324)


Response Model: 

The second phase entails the creation of a responsive system driven by AI and machine learning algorithms. This system will be integrated into autonomous VTOL platforms, enabling them to autonomously locate and track victims buried beneath avalanches. The AI-driven response model will not only pinpoint victims but also deliver comprehensive details about their condition and location. This critical information will be relayed to rescue teams, facilitating rapid and precise rescue operations, thereby minimizing response time and increasing the chances of survival.

These two phases are integral components of our mission to enhance safety and save lives in avalanche-prone regions. We remain committed to advancing technology and implementing innovative solutions to address the challenges posed by avalanches, ensuring the well-being of those who venture into these hazardous environments.

![2](https://github.com/geexpro/Ingenuity-SIH-1422/assets/88074810/f90fcb03-1831-41bb-ac84-f7127154fccc)

Your provided text is a valuable addition to the project description. It provides more technical details about the specific neural network architecture, ResUNet, and how it is applied to the context of avalanche detection. Here's a revised and expanded description that incorporates this information:


---
The AI approach in Predicting Avalanches and Rescue of buried victims
---

In our relentless pursuit of improving avalanche victim identification, we've employed the cutting-edge ResUNet neural network model. This sophisticated AI/ML technology is specifically tailored to process and analyze imagery and data pertinent to avalanche situations. By doing so, we aim to significantly enhance our ability to detect avalanches and identify individuals who may be trapped in these life-threatening scenarios.

**ResUNet: Transforming Avalanche Detection**

ResUNet represents a crucial component of our innovation. It's not just a neural network; it's a powerhouse designed to handle the intricacies of avalanche data. Here's how it elevates our approach:

1. **Customized UNet Integration:** We've tailored our very own customized UNet for the training and testing of avalanche data. This customized network specializes in avalanche detection, ensuring our model is finely tuned to the unique challenges presented by this rugged terrain.

2. **Multispectral Data Handling:** Avalanche situations often demand the integration of diverse data types, including thermal, optical, and radar imagery. ResUNet's capabilities extend to processing multispectral data, enabling us to harness the full spectrum of available information. This holistic approach significantly boosts our detection capabilities.

3. **Efficiency and Precision:** ResUNet is designed for efficiency and precision. It doesn't just analyze data; it uncovers insights, patterns, and anomalies that might be missed by traditional methods. By doing so, it empowers search and rescue teams with actionable intelligence, enabling them to make quicker and more informed decisions.

In the unforgiving terrain where every second counts, our integration of ResUNet into avalanche victim identification is poised to be a game-changer. We're committed to pushing the boundaries of technology to make the mountains safer and to improve the chances of survival for those in peril.

![hp](https://github.com/geexpro/Ingenuity-SIH-1422/assets/88074810/c40fb655-7dd1-4ffc-8e52-3925c19e2e5e)
![layer](https://github.com/geexpro/Ingenuity-SIH-1422/assets/88074810/e42355ce-8113-4acd-9ecb-70a8b78531e4)


---
Ground Control and Connect
---
**Using GCS (Mission Planner)**

In our project, we've developed a customized version of Mission Planner, 
*an open-source software platform* 
known for its capabilities in orchestrating high-performance and intelligent UAV (Unmanned Aerial Vehicle) flights. This technology forms the backbone of our innovative approach to avalanche detection and response.

Our system seamlessly integrates Machine Learning (ML) models into the Mission Planner software. These ML models receive avalanche data and leverage it to create survey regions and autonomously configure waypoints for our Vertical Take-Off and Landing (VTOL) drones.

Once activated, our VTOL drones take flight automatically and navigate to the designated survey regions. These drones are equipped with specialized sensors, which include [Insert Sensor Name]. These sensors play a pivotal role in identifying casualties in avalanche scenarios, whether they are human or animal. Importantly, they have the capability to precisely pinpoint the exact coordinates of individuals potentially trapped beneath snow debris.

The location data of these casualties is then transmitted back to our Ground Control Software (GCS), a vital component of our operation. Our GCS serves as the central hub for coordinating response efforts. It allows us to dispatch relief teams promptly to assist the casualties. Communication and remote control are facilitated through the MAVLINK protocol, ensuring seamless and efficient operations.

This integrated remote sensing system is a game-changer, dramatically reducing the time needed for search and rescue teams to locate individuals affected by avalanches. Ultimately, it significantly enhances the chances of survival for those in distress, reinforcing our commitment to avalanche safety and response excellence.

![3](https://github.com/geexpro/Ingenuity-SIH-1422/assets/88074810/cd6141ce-c206-4d3c-98dd-bd6f9420060f)

![4](https://github.com/geexpro/Ingenuity-SIH-1422/assets/88074810/97fae90a-12f8-40c9-a7bf-07340c28601a)

![5](https://github.com/geexpro/Ingenuity-SIH-1422/assets/88074810/9adbbb46-f3cb-42be-808d-efed6ad89a88)

![6](https://github.com/geexpro/Ingenuity-SIH-1422/assets/88074810/a75d756c-87a9-4006-afd7-4afeb937bbe2)


---

Getting the DataSet ready
---
Multispectral imagery plays a pivotal role in geospatial analysis, often harnessed through powerful tools like Google Earth Engine and QGIS. These images capture data across a spectrum of wavelengths, allowing us to observe a wide range of information about our planet's surface. In particular, C band, a segment of the microwave spectrum, is frequently utilized. C band radar data, commonly acquired from satellites, provides valuable insights into various Earth processes, including land cover changes, soil moisture levels, and vegetation health. With the computational capabilities of Google Earth Engine and the geospatial processing capabilities of QGIS, researchers and environmental analysts can harness multispectral imagery, including C band data, to gain deeper insights into Earth's dynamic systems, facilitating informed decision-making and sustainable environmental management.


---
Into the Avionics Subsystem
---
![0 - uav](https://github.com/geexpro/Ingenuity-SIH-1422/assets/88074810/a00a15c6-1007-48fd-8b84-3d2f430f7256)


**Sensor Systems Evaluation for Avalanche Detection**

The assessment of sensor systems for avalanche detection revealed varying degrees of capability. Of paramount importance in avalanche hazard evaluation is the ability to detect layering within the snowpack. Ground Penetrating Radar (GPR) proves instrumental in this regard. However, the layers within the snowpack can differ significantly due to factors such as surface frost and snow crystal composition. As a result, there is a need to correlate the snow layers identified by GPR with the hardness scales traditionally employed by avalanche professionals during snow pit assessments. This correlation effort is crucial to showcase that GPR can consistently and successfully locate layers of interest.

**Aerial Surveillance for Avalanche Monitoring**

In collaboration with the Norwegian Public Roads Administration (NPRA), we've harnessed a fleet of aircraft to enhance our avalanche monitoring capabilities. These aircraft are classified into quadrotors, multirotors, helicopters, and fixed-wing planes. Fixed-wing aircraft excel in winter conditions and can cover vast distances and altitudes necessary for avalanche feature observation. However, they lack the stability of multirotors, which can hover in place. Fixed-wing planes also require more complex takeoffs and landings, often involving launching catapults or parachute systems. Multirotors, on the other hand, offer stability and versatility, making them ideal for transporting sensors to specific locations.

**Airborne Sensor Technologies**

Literature review has confirmed the potential of airborne sensor technology for measuring snow volumes, intensity, and detecting vulnerable layers beneath the snow. LIDAR (Light Detection and Ranging) is a notable technology that employs pulsed laser light to measure distances to the Earth's surface. While LIDAR systems designed for Unmanned Aerial Systems (UAS) are commercially available, their usage for snow surface and avalanche hazard assessment remains limited. LIDAR holds the promise of mapping the snowpack surface and identifying avalanche indicators such as cracks.

Photogrammetry, also known as Structure from Motion (SfM), can create 3D images from multiple 2D photographs, providing valuable insights for avalanche monitoring.

**Ground Penetrating Radar (GPR)**

Ground Penetrating Radar (GPR) utilizes electromagnetic radiation pulses to penetrate the ground and capture subsurface images. Traditionally mounted on carts or sleds, GPR has recently been adapted for use on manned aircraft. This innovation has found applications in glaciology and avalanche victim search operations, enhancing our ability to locate and rescue avalanche victims.

**Aircraft Payload-Range Performance Evaluation**

To optimize aircraft performance, we perform comprehensive payload-range evaluations. This analysis considers various factors, including aircraft operational weights and their impact on payload-range performance. Specifically, we focus on Maximum Take-off Weights (MTOW) and their components to determine payload capacity at different levels and range capability with specific payloads.

For any aircraft with a specified Maximum Zero Fuel Weight (MZFW), the maximum payload can be calculated as:

```
Max Payload = MZFW – OEW (Operational Empty Weight)
```

This calculation helps us efficiently utilize aircraft payload capacity for avalanche response missions.




These technologies and evaluations collectively contribute to our mission of enhancing avalanche detection, response, and victim rescue, reinforcing our commitment to safety and excellence in avalanche management.
