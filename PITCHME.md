@title[unmanned aerial systems field operations and mission planning]
#### unmanned aerial systems (uas)
##### field operations and mission planning
###### D.J. Biddle, GISP
---
@title[the plan] 
#### the plan
- The Big Picture: Guiding Principles
- Study Area Reconnaissance: Know B4 U Go!
- Mission Plan Design: Match the application
- The Day Of: Checking the boxes 
- Aeronautical Decision Making: Cool heads prevail
- If It All Goes South: Accident Procedures
---
@title[the big picture]
#### The Big Picture!
What is our objective?...  
  
@css[fragment](Capture **high quality imagery**) @css[fragment](of our **study area**,) @css[fragment](to suit the intended **application**,) @css[fragment](in a **safe, efficient, and professional** manner.)  
  
@css[fragment](All decisions related to field operations should emanate from this simple objective!)
+++
@title[Study Area Reconnaissance]
#### Study Area Reconnaissance
##### Know B4 U Go! 
Our first task is to become familiar with the study area and its vicinity...  

  @css[fragment](general reconnaisance can be guided by a few questions.)
+++
@title[Study Area Reconnaissance]
#### Study Area Reconnaissance   
@ul[squares]
- Where is the site? @css[fragment](**lat/long/elev/area of interest?**)
- How will we access it? @css[fragment](**driving/walking/need permissions?**)
- What is the terrain? @css[fragment](**steep slopes/tall trees/obstructions?**)
- Airspace considerations? @css[fragment](**require ATC permission/nearby facilities?**)
- What type of data to collect? @css[fragment](**aerial photos/3D Models/IR imagery?**) 
@ulend
+++
@title[Study Area Reconnaissance]
#### Study Area Reconnaissance
Our main tools will be exisitng maps and imagery of the area.  
  
- [Google Maps/Streetview](https://maps.google.com)
- [Google Earth](https://earth.google.com)
- [Skyvector](https://www.skyvector.com)
- [Know B4 U Fly](http://knowbeforeyoufly.org/air-space-map/)
- [USGS Topo Maps](https://www.arcgis.com/home/item.html?id=99cd5fbd98934028802b4f797c4b1732)
+++
@title[Study Area Reconnaissance]
#### An example
<iframe width="800" height="600" data-src="https://centerforgis.maps.arcgis.com/apps/Embed/index.html?webmap=191fad03a33d4b73a2910a1a71af81aa&extent=-83.357,38.1425,-83.3427,38.1476&zoom=true&previewImage=false&scale=true&search=true&searchextent=true&details=true&basemap_gallery=true&disable_scroll=true&theme=dark"></iframe>
---
@title[Mission Plan Design]
#### Misson Plan Design
The *image acquisiton plan* that we design to capture imagery, will vary based on several factors...  
  
@ul[squares]
- Drone and camera type
- Image product priorities (2D Maps vs 3D Maps/Point Clouds, Area vs Structure)
- Area to be flown (shape and size)
- Terrain considerations
@ulend
+++
##### A quick word on image processing...
The magic of UAS imagery lies in Structure from Motion (SfM) image processing...
- 3D reconstruction based on point matching between overlapping images
- Same principle as stereoscopic imagery
 - **parallax**: displacement of an object caused by a change in the point of observation
+++
##### Image Parallax
![parallax](images/parallax.jpg)
+++
##### SfM processing from overlapping images
![Pix4D 4](images/pix4d_4.JPG)
+++
#### Misson Plan Design
We will use [Pix 4D Capture](https://www.pix4d.com/product/pix4dcapture) for planning and executing flight plans, but there are many options available, including...  
  
@css[fragment](
- [DroneDeploy](https://www.dronedeploy.com/product/mobile/)
- [DJI Ground Station Pro](https://www.dji.com/ground-station-pro)
- [UGCS](https://www.ugcs.com/)
- [Precision Flight Pro](https://www.precisionhawk.com/precisionflight)
)
+++
#### Misson Plan Design
##### Drone and Camera Type
@size[0.6em](The sensor used will define ground sampling distance/GSD of resultant imagery. The sensor's area, resolution, and lens focal length, all contribute to the calculated GSD at a given altitude.)

<iframe class="stretch" data-src="https://www.propelleraero.com/gsd-calculator/"></iframe>
+++
#### Misson Plan Design
##### Drone and Camera Type
In our mission planning software...  
  
![Pix4D Drone Selection](images/pix4d_drone.png)
+++
#### Misson Plan Design
##### Image Types
Different image priorities necessitate different flight parameters...  
  
@css[fragment](Simple 2D aerial photos/surface models demand a **nadir** camera angle with **75% frontal overlap**, and **60% side overlap**, in a simple grid pattern)  
  
@css[fragment](![flight Plan #1](images/flight_plan_1.png))
+++
#### Misson Plan Design
##### Image Types
Whereas study areas with lots of vertical structure and complex geometry may require **oblique** camera angles, and a **double grid** flight pattern to obtain enough information for 3D reconstruction.  
  
@css[fragment](![Flight Plan #2](images/flight_plan_2.png)
+++


#### Finished







 




 



