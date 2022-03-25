# IK_UserStudy_2022
IK Elbow script, Raw dara for different modes, Summarized data for participant 1-1
Raw data can be found in the folder called StreamingAssets
Elbow visualizer script can be found in the Assets folder


You will need to open a new unity project and add the ElbowVisulizer script to the main camera. 
StreaminAssets folder should be put into the Assets folder. All csv files should be located in this folder.

When trying to visualize the data with gizmos, click on the main camera, update the file you wish to read from (ensure you have .csv at the end of the file name). Once this is loaded, you can press play, the visualization will be in the scene

THE EDITOR: 

~File name -> file you are currently seeing rendered with gizmos

~Preview -> Click and drag, or type the csv line you want to jump to, if this value is <0 an error will appear in the console

~Shoulder Offset -> must be set before hitting play, this is a manipulation of the shoulders on the y axis (for accuracy to raw data, keep this value at 0)

~Seat Offset -> The green sphere is the calculated seat position based on the arm spand/2. The sphere is placed below the head and can be moved to set a visual seat. This offset (up or down on y axis) must be set before pressing play.

~Fake Seat Position -> shows the seat position coordinates in world space (this includes any offset that has been applied)
L/R Arm Length -> This shows the length of the arm(s) according to the offset of the shoulder (if shoulder offset = 0, arm lengths are from raw data)
