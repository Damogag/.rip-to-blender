# .rip-to-blender
This is a python script to import .rip files from ninjaripper into blender

you might need to change the 'dir' variable to your folder with the rip files you want to import

Stuff that works:
  >geometry import
  >normals import (?)
stuff that does not work (for now)*
  >UV-Map import
  >texture import
  >vertex group import
  >vertex weight import
  >vertex color import
  
*most of the imports are read from the file and stored in lists but i did not find a way to apply them to the mesh

feel free to contribute to the script or modify it on your own. Sharing your own modifications or improvements is greatly appreciated since the blender python ducumentation is not so great...

PS: i know the code is shit, i learned python while coding this, but hey! At least it works'ish
