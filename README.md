# MC-Load-Poses-On-Selected-Frames
On each selected frame, this script reads the Master Controller's current position and then load the pose that corresponds to the position. 

	MC Load Poses On Selected Frames v1.0
	
	On each selected frame, this script reads the Master Controller's current position and then load the pose that corresponds to the position.
	You can load poses from Master Controller rigs created with Interporation Grid and Slider Wizards.
	
	This script is basically mcPoint2dInterpolation.js and mcInterpolationSlider.js being repurposed.
	The two script above and their helper library are written by (C) 2017-2019 Toon Boom Animation Inc.
	
	
	Compatibility:
	
	Tested on Harmony Premium 16.0.3 and 17.0.0. 
	MC rigs made in Harmony 15 are not supported.
	Also this script has a compatibility issue when load a Harmony 17 MC rig on Harmony 16 and then try to use this script to load poses.
	MC rig made in Harmony 16 seem to work fine on Harmony 17 with this script.

	
	Installation:
	
	1) Download and Unarchive the zip file.
	2) Locate to your user scripts folder (a hidden folder):
	   https://docs.toonboom.com/help/harmony-17/premium/scripting/import-script.html	

	3) Add all unzipped files ( *.js, *.ui and script-icons folder ) directly to the folder above.	
	4) Add MC_Load_Poses_On_Selected_Frames to any toolbar.
	
	
	Direction:
	
	1) Select Master Controller node(s) or its parent group.
	2) Run MC_Load_Poses_on_Selected_Frames.	
	3) If no nodes are selected, script will make a list of all Master Controllers in the scene.
	4) On the Master Controller List, check ones to load poses from.
	5) Set a frame range for the script to process by selecting frame(s) in Timeline view.
	   The selection does not need to include actual member nodes that the selected Master Controller controls.
	6) Push Load Poses button.
	7) You can also use Show MC button to show the control widget of the checked Master Controller in Camera view.
	
	
	Required Scripts:
	
	This script relies on the library of Harmony 16/17's Interpolation Slider/Grid scripts, which comes with the standard Harmony Premium software. 
	
	
	Coder:

	Yu Ueda (raindropmoment.com)
