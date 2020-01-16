# VIRES VTD

| Files  | Version  | Date |
| :------------ |:---------------|:-----|
| ZalaZONE_full.opt.osgb     | 0.1 | 01.16.2020. |
| ZalaZONE_full.opt.tdo    | 0.1 | 01.16.2020. |
| ZalaZONE_full.xodr     | 0.1 | 01.16.2020. |

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


### 4.2. Low-Speed Handling Course

MISSING

### 5. Smart City Zone

Features
- Contains road markings and some traffic signs.

Limitations
- The small roundabout is missing.
- Car park line markings are missing.
- Bike lanes with driving lanes sometimes work incorrectly.

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

![](https://raw.githubusercontent.com/BMEAutomatedDrive/ZalaZONE-test-track-simulation-models/master/VTD%20VIRES/Pictures/ZALAZONE02.png?token=ANMC4MNMM2JVYNHQQQO5ODS6EB4SK)
