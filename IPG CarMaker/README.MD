# IPG CarMaker

| Files  | Version  | Date |
| :------------ |:---------------|:-----|
| ZalaZONE_full_v01.rd5 (zipped)     | 0.1 | 01.16.2020. |

All of the modules based on the original plans and are created manually in Scenario/Road editor (IPG CARMAKER's own road-network designer software). There are minor deviations from the constructed test track. 

Features
- The whole area is ready for driving (by IPG driving model or by steering wheel hardware too)

Limitations
- Software cannot generate an accurate terrain: some elements are under the ground.
- Putting a layer on an other layer makes vibrations.
- The elevation relations between the modules are not accurate.

***

## Modules

### 1. High-speed oval

Features
- Contains road markers/lane markings and traffic barriers.

Limitations
- The road cross sections of the banked curves are not accurate.

Other
- The road is made of five lanes. The IPG driver model can use the lanes separately. A human user with steering wheel hardware can drive on the whole road width.

### 2. Dynamic Platform

Features
- Built from multiple lanes connected logically. A human user with steering wheel hardware can drive freely on the whole platform
.
- Contains parking area and acceleration triangle section.

Limitations
- There are some visualization bugs in the 3D viewer mode (black lines on the surface).

Other
- Made of junctions and lanes with 150 m width.

### 3. Braking Platform

Features
- All the lanes are in the same direction
.
- Every special braking surface have textures and friction settings (appropriate from visualization and basic vehicle dynamics point of view).

Limitations
- There is no CRG file for the surfaces.
- The width of the left side of the road is not realistic.

### 4.1. High-Speed Handling Course

Features
- Consists of 3 right lanes. The IPG driver uses the whole center lane width, but not the side lanes (gravel bed).
- The two road side lanes have special texture and friction (gravel).
- Built based on the planned elevation profile.

Limitations
- There is no 3D surface for gravel bed in visualization.

### 4.2. Low-Speed Handling Course

Features
- Junctions and roundabouts are made of ramps.

Limitations
- Grass is missing at some places.

### 5. Smart City Zone

Features
- Contains all special Hungarian traffic signs from the plans.
- Contains 2 special roundabouts.
- Contains road marks/lane markings and traffic barriers.

Limitations
- Lane widths are not accurate everywhere (due to road generation issues).
- Large vehicles cannot take all the turns, because the rear wheels go out of the road causing simulation error.

Other
- IPG road designer does not have roundabout type road. Roundabouts can be built from other road types. 

### 6. Motorway 

Features
- Contains road markers/lane markings and traffic barriers.
- Contains one lane roundabouts.

Limitations
- There is no terrain in the roundabout.

### 7. ADAS surface

Features
- Consists of two lanes.

### 8. Rural/Connection roads

Limitations
- Does not contain the whole planned road network.
- The road elevation profile is not accurate.

***

![](https://github.com/BMEAutomatedDrive/ZalaZONE-automotive-proving-ground-virtual-simulation-models/edit/master/IPG%20CarkMaker/Pictures/IPG_oval.JPG)
