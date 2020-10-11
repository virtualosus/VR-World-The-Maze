# VR-World-The-Maze
Git Hub of Assignment 1
Sebastian Vowles
2030428
08.10.2020

Assignment 1: Virtual Worlds of EG-M126 of the VR MSc for Swansea University

Title:			The Maze
Mozilla Hubs Link: 	https://hub.link/9VoAdYi  
.zip File Name: 	The Maze
Unity Version:		2019.4.10


Building on what was learned during the development of the first assignment walkthrough, this virtual world was 
designed to submerge the user in a dungeon style environment so that they could explore a small and simple maze 
and reach the top (third) floor. 

The idea was to use visual cues to guide the user around the area (green flags on the wall), so that they could 
not get disorientated, and other objects were used to block their way when trying to access the wrong direction 
(large jars). The general purpose of the application was to be a bit of gaming fun, using strong stylisation to 
aid with the immersive experience, whilst aiming to meet the marking criteria.
 
The first additional feature used was that of text, which was to help clearly explain to the user what they were 
to do within the world, and then used in a second location to congratulate them on completion of the task. In the 
Mozilla Hubs build, this is used slightly differently upon completion, where the user can find a comments board 
which they can use to leave a message using the built in tools of Mozilla Hubs, as well as to describe the music 
player and some additional sound effects which the user can activate and control.

The second additional feature in the app was the use of a background music track. This looped piece of music was 
added to help with the immersion and to support the stylisation of the dungeon in general. As mentioned above, 
there were some additional sound effects applied with an interactable player in the Mozilla build, so the users 
could utilise them. This was based on the idea of multiple users being in the app at the same time, and sharing 
the experience. Someone that had already reached the final area could then activate some spooky sounds to ‘scare’ 
their fellow users, and enhance the immersive experience.

When reflecting upon this piece, I realise that I spent a lot of time focusing on trying to get it to work and 
look how I wanted within the Mozilla Hubs environment the most, and perhaps over complicated it for myself generally. 

I found myself trying different ways to include the text element that would carry through our prescribed workflow, 
with varying degrees of success. The TextMesh Pro function within Unity works great for the XR build, but would not 
export to .obj, which could then be used for creation of the .gtlf file for use in Mozilla Hubs. 3D text was then 
tried, but this increased the polygon count well beyond what was recommended within the Hubs environment, so could
not be used either. Ultimately, 2D text was added to the .obj once it had been exported from Unity and was in Blender, 
and then exported together from there as the .gtlf, which worked well and did not affect the polygon count. The TextMesh 
Pro was kept for the XR build. Trying out and investigating the different possibilities did consume more time than I 
would have liked, but did help improve my knowledge of the available options and their restrictions for future projects.

I had also initially thought to use light as a means of visual cue to guide the user around the maze and spent some 
time investigating and attempting to make this work, with the correct path being light by candles instead of the use 
of flags. This again ultimately proved fruitless due to the restrictions of the file formats being used for the Hubs 
build, but could have worked well in the XR build. Further, the recommended number of lights within Hubs would not 
have allowed for this either. Once this option had been thoroughly looked at, the flags option was decided upon so 
that the two builds would be as close as would be reasonable.

Overall I feel that the world experience did come across as I had initially envisaged, and I am pleased with the 
fact that I was able to overcome some of the technical restrictions and difficulties to complete the piece. I do 
think though, that I probably over complicated this for myself generally, and was perhaps looking at the task from 
more of a game perspective than as a virtual world. By making it so enclosed and claustrophobic I was limiting what 
I could do and the experience I could give, even though this design was as was initially intended. If the task were 
to be set again, I would likely go a very different route, with an open plan environment and a different sense of 
exploration.

Asset Credit:		Dungeon Stone Textures by 3D.Rina
			          Low Poly Dungeons Lite by JUSTCREATE
			          Pro Builder by Unity
			          TextMesh Pro by Unity

References:		Beginners Blender Video no. 9: 3D Text - bpwebmedia 
              https://www.youtube.com/watch?v=SYLB8ejaNC4&ab_channel=bpwebmedia
			Lighting Manual - Unity
              https://docs.unity3d.com/Manual/Lighting.html
	              UV Editor Guide - Blender
              https://docs.blender.org/manual/en/latest/editors/uv/index.html
	              XR Rig Manual - Unity
              https://docs.unity3d.com/Manual/XR.html
