# ARMOT-dataset
Dataset for Multi-Object Tracking from Aerial videos for Rescue missions (ARMOT, Aerial Rescue Multi-Object Tracking).

In the absence of aerial datasets with available ground truth annotations about the position and identity of multiple human beings for search and rescue purposes, a new dataset has been captured from this platform:
a carbon fiber octocopter of total weight 4Kg, equipped with GNSS, magnetometer and IMU (accelerometers, gyroscopes, and barometer). Furthermore, a down-looking camera Kinect v2 which provides 1920x1080 RGB images, is used as the main sensor. 

This new dataset, called ARMOT dataset, Aerial Rescue Multi-Object Tracking dataset, is formed by the following four video sequences, listed in order of increasing difficulty:

1. Urban scenario with hovering mode UAV on static human bodies.
2. Urban scenario with hovering mode UAV on dynamic human bodies (walking and jumping), with periods of blurred frames.
3. Open arena with high velocity flight and static human bodies.
4. Open arena with high velocity flight with several disappearances and re-appearances of the people in the field of view.

The following table presents the video specifications values for every sequence.


| SEQs | Framerate (FPS) | Resolution | Length (frames) | Duration (s) |
| :--: | :-------------: | :--------: | :-------------: | :----------: |
|   1  |        15       |   960x540  |       221       |      14      | 
|   2  |        30       |   960x540  |       251       |       8      |
|   3  |        15       |   960x540  |       120       |       8      | 
|   4  |        15       |   960x540  |       645       |      43      |


In addition, every video sequence is accompanied by its corresponding annotations. These consists of the bounding boxes and identities of every human detection at each frame, as long as they are occluded in less than the 50\% and their head are visible. This information has been collected in xml files. 

The described sequences form the fist version of the ARMOT dataset, which is meant to be enlarged with a wider variety of aerial video sequences. 


# Access
The video sequences can be found here:https://drive.google.com/open?id=16SwZ_XwjGYJvv7jSKeIu_LQsK68F16Rk
The annotations are in the folder with te same name (ANNOTATIONS) in this repository.

