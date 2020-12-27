See below for a short list of things I learned while starting to work with workadventure. See [official workadventure github page](https://github.com/thecodingmachine/workadventure-map-starter-kit) for a more generic introduction. See the [official rc3 page](https://howto.rc3.world/) for additional info on builing maps. 

# Getting started the easy way

- Clone this repository
- Install [Tiled editor](https://www.mapeditor.org/)
- Oben "robby.json" in Tiled
- Start editing

# Lessones learned while building 

- If you want to have multiple jitsi video sessions in one map, create a single layer for each jitsi conference
- If you don't embed all tilesets into the map in Tiled before pushing to github, the map will not load and will not display any errors
- If you want to have a object that can not be moved through, open the tileset editor in Tiled and change/add a boolean property named "collides", set to "true". 

## Working with layers

- In Tiled, always select the layer you want to work on. 
- Create dedicated layers for certain elements. E.g., put all basic furniture into a single "objects" layer.
- The start layer is mandatory, and will spawn persons entering the map on any tile that is available in this layer (even if tiles are not visible). 
- If you want to put elements on top of other elements (e.g. position a beer glass on a bar table), put the lower object (bat table) on a lower level, and the higher object (beer glass) in the same location, but on a higher layer. 

# Lessons learned while using workadventure

- This tool is amazing. The combination of very well working jitsi integration, and the option to see how is also on the map, is great. If you see that on another table there are people you want to talk to, just walk your character over there. 
- Jitsi conferences work much better than the 2-4 persons just standing close to each other. 
