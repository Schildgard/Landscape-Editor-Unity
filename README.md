# About

The Landscape editor was part of my second semesters module. The point was to build an engine tool that significly reduces my workload.
While working on my Bonfire project, I realized that Unitys Terrain System does not fit my needs. Building an authentic environment by hand takes an
tremendous effort, experience, passion and skill. Thus I decided to build my engine tool around that problem.  
This tool not only creates a plane which can be shaped by adjusting its attached Shape Settings, it also places environmental assets.


## Plane Manager
A program that creates a plane and shapes it due to parameters given in the shape editor settings.  
It is supposed to be used to build landscape with authentic hills and mountains with just a few clicks.


## Terrain Shader
A Shader that takes up to two textures and blends betweeen them due to parameters like normal direction and world-Y-Position.  
It allows to seperate what is supposed to be ground and what is supposed to be mountain.

## Environment Manager
Places environmental elements on a mesh depended it adjustable parameters.
### Environmental Vegetation
Vegetation takes a material and a model as Input. It renders an amount of instances of that on the mesh surface via GPU Instancing, the amount is dependent on the threshold value (-1 renders everywhere, 1 renders nothing). 

### Prefabs
Take Prefabs as Input and places it on random positions on the mesh surfaces. 

---
This Readme is still under construction
