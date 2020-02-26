# VIRES VTD

| Files  | Version  | Date |
| :------------ |:---------------|:-----|
| ZalaZONE_full.opt.tdo    | 0.2 | 02.26.2020. |
| ZalaZONE_full.xodr     | 0.2 | 02.26.2020. |

Laser scanned and blueprint-based models of the Smart City Zone of the ZalaZONE test track in OpenDrive (.xodr) format. The full test track model was created manually in ROD (VIRES own road-network designer software) based on the original plans. There are minor deviations from the constructed test track. The provided file is in .tdo which is the working file of the ROD. For the scenario editor .xodr and .osgb are also provided.

Features
- The whole model can be exported to .xodr (OpenDRIVE)

Limitations
- All elevations are missing.
- Some modules are missing.
- Most of the road marks and traffic signs are missing.
- Environmental objects are missing (trees, houses, etc.).
- Road-surface models (OpenCRG) are missing.

***

## Modules

### 1. High-speed oval

Features
- It consits of five lanes, every lane has an own path (or center-line)

Limitations
- The curves are not banked and they have no elevation.

### 2. Dynamic Platform

Features
- The original lanes are hidden. For the right visualization, an independent layer is created with 1 lane with 150 m radius connected to a junction (in 360 degrees).
- Built from 5 circle-sectors and 4 junctions to have the acceleration triangle and exits.

Limitations
- No safety zone (run-off area) and guardrail.
- There are intersecting elements.

v0.2 changes
- Junction at the entrance of the Dynamic Platform has been fixed.

### 3. Braking Platform

Features
- Consits of 10 separate lanes.

Limitations
- No exit or turn-back lane on this platform.
- The different braking-lanes have the same friction and roughness.
- No guardrails.
- No elevation.


### 4.1. High-Speed Handling Course

Features
- The path is accurate based on the original 2D plans
- Contains the safety zone (run-off area) for the right visualization

Limitations
- No elevation.
- Missing physically realistic safety zone.
- No guardrails.
- Missing road-markings.

v0.2 changes
- 0,1 m lanes have been removed.


### 4.2. Low-Speed Handling Course

MISSING

### 5. Smart City Zone

Features
- Contains road markings and some traffic signs.

Limitations
- The small roundabout is missing.
- Car park line markings are missing.
- Bike lanes with driving lanes sometimes work incorrectly.

v0.2 changes
- Road "BME scenarios" has been deleted

### 6. Motorway 

Features
- Contains two driving lanes and an emergency lane in each direction.

Limitations
- No exits and entries yet.
- The elevated junction is missing.

### 7. ADAS surface

MISSING

### 8. Rural/Connection roads

Features
- One lane in each direction with junctions.

Limitations
- No elevation. 
- Some road sections are missing yet.

***

![](https://github.com/BMEAutomatedDrive/ZalaZONE-automotive-proving-ground-virtual-simulation-models/blob/master/VTD%20VIRES/Pictures/ZALAZONE02.png)

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
