Ancient Gem freeshell v1.0.1
for Etc. Jam 2025

Holy gemstones! Your adventures in this cave have led you all the way to the gem queen! What will you do now? What will happen to you?

Well... that's up to you now, isn't it :)

Also check out the matching balloon and calendar skin!
https://ukagaka.zichqec.com/balloon/ancient_gem_balloon
https://ukagaka.zichqec.com/calendar_skin/ancient_gem_calendar

This shell was made to pair with the freeshell Forged Metal, by Galla. Check that one out as well! You can use them together or separately.
https://github.com/GallaTheGalla/forged_metal/releases/latest


—————————— Terms ——————————
This freeshell is free to use for your own ghost projects, with the following terms.

You must:
	• Mention in your ghost's readme that you are using my freeshell. I can be credited as "Zichqec", with the following link: https://ukagaka.zichqec.com/
	• List any modifications you have made to the freeshell's artwork in your ghost's readme.
	• Keep this readme file as-is. (It can be renamed if you are combining this freeshell with other freeshells.)
	• Keep the craftman information of the freeshell as-is. (If combining this freeshell with other freeshells made by different developers, the craftman information can be modified to ensure all developers are represented.)
	
You may:
	• Modify the shell, including recoloring, drawing new expressions, combining expressions, scaling the images, mirroring the images, etc. (This shell is drawn in a pixel style, please take care when scaling. It'll look best if you keep the pixels sharp!)
	• Modify the settings files in any way you need.
	• Combine this shell with other freeshells.
	• Use this shell to create a thumbnail image for your ghost, or a preview image for use on the ghost's release page, etc.
	
You must not:
	• Distribute any version of this freeshell on its own.
	• Use this freeshell to create commercial works.
	• Use this shell for works outside the realm of ukagaka.
	• Modify the shell to be discriminatory or political, or use it in a work that contains these elements.
	• Modify the shell to add nudity or sexual elements.
	• Use AI tools to modify the artwork in this shell.

It is not required to notify me that you have used this shell, but I'd love to see what you've made!


—————————— Customization ——————————
layers.psd has been included to help with customization. Feel free to make use of it for recoloring, adding patterns, etc.

The surface numbering is set up in such a way that it should be easy to combine with the Forged Metal freeshell without having to renumber very many things.

By default, the gemstone eye color is controlled by a dressup. However, a quick and easy customization would be to delete the dressup definitions in descript.txt, and in surfaces.txt change all the binds to a never interval instead (except for the first gem, which should be runonce).
Then, instead of the user controlling the gem color, you could control the color with \i[] tags in your scripts and use it to indicate things such as the character's mood or some other status. I think that could be a fun option.

I think you could conceivably stitch together the different head variations to create a head tilting animation for the forward facing heads, and a nodding animation for the other heads. I'm not an animator so it might be a little janky, but feel free to try it.


—————————— Surface numbering scheme ——————————
This shell doesn't use the standard surfaces listed on Ukadoc because... well, it doesn't have much of a face. Instead, there are 3 directions the head can face, and 2 variations of each direction. There's also one unique head I threw in as a bonus.

Surface 0-2 - Facing fully towards the user
	1 - head tilted towards the right side of the screen
	2 - head tilted towards the left side of the screen
	
Surface 3-5 - Facing at a 3/4 angle, face partially in shadow
	4 - Head tilted upward
	5 - Head tilted downward

Surface 6-8 - Facing towards the right side of the screen, gem eye not visible
	7 - Head tilted upward
	8 - Head tilted downward

Surface 9 - Head bowed (facing the user)

There are also separately poseable arms specified as animations, which you can call with \i[] tags in your scripts. The arms are the same across all surfaces.
Note: When changing to individual arms rather than both arms together, you will need to specify both a left arm and a right arm at the same time, or else only one arm will display. The default arm position is one with both arms together, so you will need to do this each time you change surfaces.
(Of course, you can also use the shell with only one arm if you prefer it.)

Animation 20-39 - Left side arms
	20 - Resting on the upper leg
	21 - Resting on the floor
	22 - Resting in lap
	23 - Gesturing forward
	24 - Gesturing to the left
	25 - Pointing up
	26 - Gesturing up

Animation 40-59 - Right side arms
	40 - Holding the upper leg
	41 - Resting on the floor
	42 - Resting on the lower leg
	43 - Gesturing backward / to the right
	44 - Gesturing downward / to the right
	45 - Pointing up
	46 - Gesturing up

Animation 60-79 - Both arms together
	60 - Both arms resting together on top of the knee (default arm position)


—————————— Collisions ——————————
The following collisions are included by default:

eye - The gem eye on the right side of the face
socket - The empty eye socket on the left side of the face
crown - The 5 spikes on the top of the head
ears - The other spikes on the side of the head (2 on each side)
face - all areas of the face that are not covered by another collision

The collision image files also include a colored region for the back of the head. I decided not to make it a default collision, but if you want to add it the rgb values are noted in surfaces.txt.