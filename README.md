UCSDUnfoldingMaps
=================

> This is a map application that gives a visual representation of earthquake information
            that is obtained in real-time, organized according to their magnitude, and represented in
            a GUI. The project uses the Unfolding library (http://unfoldingmaps.org/).The map displays a marker on the
            specific city where the earthquake occurred, the size and color of the
            marker are based on the magnitude of the earthquake.The main concepts are inheritance and
            polymorphism, to extend the earthquake marker to city marker, island marker, ocean marker, etc. 

Installation
------------

Import this folder in Eclipse ('File' -> 'Import' -> 'Existing Projects into
Workspace', Select this folder, 'Finish')  
  
If things don't work, try ('Project' -> 'Clean') before running.


Manual Installation
-------------------

If the import does not work follow the steps below.

- Create new Java project
- Copy+Paste all files into project
- Add all lib/*.jars to build path
- Set native library location for jogl.jar. Choose appropriate folder for your OS.
- Add data/ as src


Troubleshooting
---------------

Switch Java Compiler to 1.6 if you get VM problems. (Processing should work with Java 1.6, and 1.7)


