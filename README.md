# fake_laser_measurement_MATLAB
Fake laser measurements from occupancy grid map

When you run the FakeLaserRead.m script
1) Reads map from a file with ".pgm" extension and its properties from a file with ".yaml" extension
2) Asks to select a suitable free point on the map
3) Generates fake laser measurements according to laser scanner range and resolution settings
4) Draws selected point (blue color), fake laser measurements on map (red color), and laser range circle (dashed-black color)

Example for mymap in maps folder

Asking point selection for maps/mymap

https://github.com/yilmazabdurrah/fake_laser_measurement_MATLAB/blob/main/figures/SelectPointMap.png?raw=true

Drawn fake laser measurements for maps/mymap, laserRange = 5 m, laserResolution = 0.25 degrees

https://github.com/yilmazabdurrah/fake_laser_measurement_MATLAB/blob/main/figures/FakeLasersMap.PNG?raw=true

Example for mymap2 in maps folder

Asking point selection for maps/mymap2

https://github.com/yilmazabdurrah/fake_laser_measurement_MATLAB/blob/main/figures/SelectPointMap2.png?raw=true

Drawn fake laser measurements for maps/mymap2, laserRange = 30 m, laserResolution = 0.25 degrees

https://github.com/yilmazabdurrah/fake_laser_measurement_MATLAB/blob/main/figures/FakeLasersMap2.PNG?raw=true

