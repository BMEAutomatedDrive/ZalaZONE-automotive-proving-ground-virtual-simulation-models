# PreScan

| Files  | Version  | Date |
| :------------ |:---------------|:-----|
| ZalaZONE_braking_platform.pof     | 0.1 | 01.21.2020. |
| ZalaZONE_dynamic_platform.pof     | 0.1 | 01.21.2020. |
| ZalaZONE_handling_course.pof     | 0.1 | 01.21.2020. |
| ZalaZONE_high-speed_oval.pof     | 0.1 | 01.21.2020. |
| ZalaZONE_rural_road_highway_motorway.pof     | 0.1 | 01.21.2020. |
| ZalaZONE_smart_city.pof     | 0.1 | 01.21.2020. |
| ZalaZONE_smart_city.pof     | 0.1 | 01.21.2020. |
| ZalaZONE_full.7z (split)     | 0.1 | 01.21.2020. |

All of the modules based on the original plans and are created manually in Prescan's GUI. There are minor deviations from the constructed test track.

Features
- All the paths are accurate based on the original 2D plans. 
- All of the modules are available separatly in diffrent files (folders) and in .pof (Prescan Object File)*.

Limitations
- GPS coordinates are not assigned to the segments.
- In some cases elevation profiles are not accurate.

Other
- The built enviroment model has no files which describes only the road network or environment. All files from the folder are needed.

***

## Modules

### 1. High-speed oval

Features
- The path is based on the original 2D plans.
- Made of 4 lanes (same direction).

Limitations
- Bank angle is limited (max. 20°)

### 2. Dynamic Platform

Features
- The path isbased on the original 2D plans.
- Diameter of the platform is 300 m.
- Made of two roundabouts (there is no inherited path between these two segments)

Limitations
- No elevation.
- Guardrail missing.

### 3. Braking Platform

Features
- All of the lanes have the same direction.
- Every special braking surfaces have different textures.
- The path isbased on the original 2D plans.

Limitations
- No elevation.
- There is no inherited path between these braking surfaces.
- The friction of the surfaces are not set (all have the same basic value).
- "Layers on layers" warning, but there is no visual interference.

### 4.1. High-Speed Handling Course

Features
- The path isbased on the original 2D plans.
- Created using 2 lanes (1 right-hand lane, 1 left-hand lane) allowing the Prescan driver to use the whole lane width.
- There are guardrails on both sides.
- Built based on the planned elevation profile.

Limitations
- No friction set on road surfaces.
- The is no safety zone (run-off area).
- Missing road-markings.


### 4.2. Low-Speed Handling Course

Features
- The path isbased on the original 2D plans.
- Created using 2 lanes (1 right-hand lane, 1 left-hand lane) allowing the Prescan driver to use the whole lane width.
- There are guardrails on both sides.

Limitations
- There is no friction set on road surfaces.
- Missing road-markings.
- Elevation is not accurate.

### 5. Smart City Zone

Features
- Contains 2 special roundabouts.
- Containes all the separeted parking yards.
- Contains road markers and some traffic signs (but no all of them).

Limitations
- No special traffic signs from the plans.
- 60% traffic signs and road marks/lane markings are missing.
- Lane widths are not accurate everywhere, caused by limited road segments.
- No elevation.
- Bicycle lanes are separated from other roads.

### 6. Motorway 

Features
- Paths are connected.

Limitations
- Road elevation profile is not accurate.

### 7. ADAS surface

MISSING

### 8. Rural/Connection roads

Features
- Paths are connected.

Limitations
- Road elevation profile is not accurate.


***

![](https://github.com/BMEAutomatedDrive/ZalaZONE-automotive-proving-ground-virtual-simulation-models/blob/master/Prescan/Pictures/Prescan_SC_01.jpg)

***
# References
If you have found the models useful in your work, please, cite one of our papers in your publication, e.g.

Tettamanti T., Szalai M., Vass S. and Tihanyi V. (2018) "Vehicle-In-the-Loop Test Environment for Autonomous Driving with Microscopic Traffic Simulation", In 2018 IEEE International Conference on Vehicular Electronics and Safety (ICVES). Madrid, Spain, Sept, 2018. , pp. 1-6. 
URL: https://ieeexplore.ieee.org/document/8519486

Horváth M.T., Lu Q., Tettamanti T., Török Á. and Szalay Zs. (2019) "Vehicle-In-The-Loop (VIL) and Scenario-In-The-Loop (SCIL) Automotive Simulation Concepts from the Perspectives of Traffic Simulation and Traffic Control", Transport and Telecommunication Journal. Vol. 2(20), pp. 153-161. 
URL: https://content.sciendo.com/view/journals/ttj/20/2/article-p153.xml

Németh H., Háry A., Szalay Zs., Tihanyi V., Tóth B. (2019) "Proving Ground Test Scenarios in Mixed Virtual and Real Environment for Highly Automated Driving", In: Proff H. (eds) Mobilität in Zeiten der Veränderung. Springer Gabler, Wiesbaden. pp 199-210.
URL: https://link.springer.com/chapter/10.1007/978-3-658-26107-8_15

Szalay, Zs., Hamar, Z. and Nyerges, Á. (2019) "Novel design concept for an automotive proving ground supporting multilevel CAV development", International Journal of Vehicle Design, Vol. 80, No. 1, pp.1–22.

***
