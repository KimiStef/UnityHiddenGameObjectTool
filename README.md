# HiddenGameObjectTool
Simple tool for unity to check if there are the hidden gameobjects in the scene. 

Really useful for that one single unity bug which randomly marks 2D gameobjects as hidden (which they clearly aren't), moves them to zero point (Vector2.zero) and also makes them unclickable...


How to use:
- Download the script or copy it. Then if the script is properly attached to your project you can find 'Hidden GameObject Tools' on the 'Tools'-tab and if you click it opens a new window.
- Click the "Refresh" to see if there are hidden objects. Or click 'Test' which creates a new hidden empty gameobject.
- Now you have three options to choose from: 'Select', 'Reveal' and 'Delete'
- 'Select' the gameobject and show it on the 'inspector'-tab.
- 'Reveal' the gameobject on 'Hierachy'-tab.
- 'Delete' the gameobject.


* I haven't tested all the unity versions, but it works atleast from 2020.3.19f1 and later *
