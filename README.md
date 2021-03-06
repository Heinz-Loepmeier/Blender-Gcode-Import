# Blender-Gcode-Importer
G-code importer with some extra functionalities to convert from G-code to Blender mesh.  
Having access to the toolspaths directly let's you do some interesting things conventional slicers can't do.  
I've been using the importer in conjunction with <a href="https://github.com/alessandro-zomparelli/gcode-exporter">Alessandro Zomparelli's Gcode exporter</a> for Blender.


For some Blender operations it helps if the paths are evenly segmentized to give some modifiers the necessary resolution.  
Use the 'subdivide' option in the importer for that.

Another option is to split the layers into single Blender objects, makes editing or animating them easier.  
You can find some more examples <a href="https://github.com/Heinz-Loepmeier/Blender-Gcode-Import/wiki">in the wiki.</a> (16MB of .gifs)

<img src=https://raw.githubusercontent.com/Heinz-Loepmeier/wiki-sources/main/gcode-importer-docs/import.gif>

### Compatibility
Add-On works with Blender 2.8. I tested with G-code from Slic3r and Cura.  
All G1 and G0 commands with an E-value get drawn as an edge. (Travel lines get omitted)




