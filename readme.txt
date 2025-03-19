NOTE: This freeshell is not fully complete yet! It is in a usable state, but in the next week or so I hope to release an update with several arm variations. You'll see it's set up with arms as a runonce animation, and this is why. Feel free to use it in the meantime, but just know I do have more planned!

Ancient Gem freeshell v1.0.0
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
	• Keep this readme file as-is. (Exception: it can be renamed if you are combining this freeshell with another freeshell and need to retain both readme files.)
	
You may:
	• Modify the shell, including recoloring, drawing new expressions, combining expressions, scaling the images, mirroring the images, etc. (This shell is drawn in a pixel style, please take care when scaling. It'll look best if you keep the pixels sharp!)
	• Modify the settings files in any way you need.
	• Combine this shell with other freeshells.
	• Use this shell to create a thumbnail image for your ghost, or a preview image for use on the ghost's release page, etc.
	
You must not:
	• Use this freeshell to create commercial works.
	• Distribute any version of this freeshell on its own.
	• Use this shell for works outside the realm of ukagaka.
	• Modify the shell to be discriminatory or political, or use it in a work that contains these elements.
	• Modify the shell to add nudity or sexual elements.
	• Use AI tools to modify the artwork in this shell.

It is not required to notify me that you have used this shell, but I'd love to see what you've made!


—————————— Customization ——————————
I have not yet included a psd file with this shell because it is not complete. I will do so when I update it for easier customization of colors, etc.

The surface numbering is set up in such a way that it should be easy to combine with the Forged Metal freeshell without having to renumber very many things.

Currently, the gemstone eye color is controlled by a dressup. However, a quick and easy customization would be to delete the dressup definitions in descript.txt, and in surfaces.txt change all the binds to a never interval instead (except for the first gem, which should be runonce). Then, instead of the user controlling the gem color, you could control the color with \i[] tags in your dialogue and use it to indicate things such as mood. I think that could be a fun option.

I think you could conceivably stitch together the different head variations to create a head tilting animation for the forward facing heads, and a nodding animation for the other heads. I don't think I'll set it up for that, but feel free to try it.


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

Currently there is only one arm pose available and it is always on, but once I add the other arms I want I'll detail them here!


—————————— Collisions ——————————
No collisions yet but I'm hoping to add some when I update it... I'll just make the note here that I'm considering the side spikes to be "ears" and the top spikes to be a "crown". But of course, interpret it as you like.