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

![](https://raw.githubusercontent.com/BMEAutomatedDrive/ZalaZONE-test-track-simulation-models/master/Prescan/Pictures/Prescan_SC_01.jpg?token=ANMC4MM3HVF6PFUME22FKIS6EB4LQ)
