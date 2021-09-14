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

## Demo
![132115482-c4f3bcdc-4db0-4cae-8ac0-b16ae35d0fa3](https://user-images.githubusercontent.com/74885386/133300314-cedec59f-f0ab-4519-9a63-40eec149992f.png)
![132115483-45805eb9-496d-42dc-a181-8116a0dd6d5e](https://user-images.githubusercontent.com/74885386/133300321-6e39c678-8b66-4c50-8dd1-a39d04537745.png)


