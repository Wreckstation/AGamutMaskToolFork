# AGamutMaskToolFork

An offline version of The Gamut Mask Tool made by Richard Robinson, with a couple of tweaks I added myself. The original gamut mask concept is by James Gurney. I'm also hosting it over on [my own github page](https://wreckstation.github.io/AGamutMaskToolFork/The%20Gamut%20Mask%20-%20FREE%20Interactive%20color%20harmony%20tool%20for%20painters.html). You can still visit and use the [original free online version here](https://mypaintingclub.com/blog/post/39-The-Gamut-Mask-Tool) if you don't like this one.

# Stuff I changed:
* Third wheel that is the YURMBY wheel but with the colors blended together, if you decided that the pallet was too limiting.
* The yurmby wheel's orange color was fixed.
* Third slider that controls the size of the gamut mask.
* Since size slider made some masks obsolete, masks 11, 12, and 20 were replaced with new shapes (right scalene, right scalene (horizontally flipped), and rectangle)
* Button next to the print button that resets sliders and color wheel rotation to their default.
* Button that randomizes the mask and wheel rotation if you don't have any ideas.
* Updated link to homepage.
* Removed telemetry related scripts like google tag manager, pintrest/fb widgets

Stuff I might do later:
* night mode
* less obviously placeholder ui
* more flexible layout
* toggle to "lock" parameters when randomizing

# How to use
Should be self explanatory, but other things less documented:
* You can click and drag the rim of the wheel to rotate it
* You can click and drag the mask shapes to move them around too
* You can right click -> copy the wheel to paste into any art program you want

The actual colors are your limited color pallet. Select a handful of colors, at the very least the ones at the corners of the mask; those will be your most saturated colors. All you can paint with are now these colors and a combination thereof. Altering the value (HSV) or luminosity (HLS) of each color is highly recommended.

# Limitations
Observations from my own usage:

As it is designed with physical paint in mind, the concept of adding pure white in reality is not the same as increasing value/luminosity. this leads to slightly washed out colors. To replicate the "true" gamut that digital painters can use, the straight lines should be polarized to give a more rounded edge to all shapes. My next planned update will be adding shapes to better fit this.

Blending also loses some vibrancy. If you need a color in between the ones the tool gives you, I suggest using your art program of choice's color wheel and move the hue slider so it's in between the two colors instead of trying to blend the two colors together. I created the continuous yurmby wheel as an attempt to mitigate this issue.

Conclusion: Unless you have Rebelle 5 Pro that has realistic color mixing, I suggest not using these as a hard guideline for digital art. Think of it as a map of where your sliders should generally be instead of directly color picking from it. I'm also not a professional artist lol. maybe the wheel was too powerful for me

![image](https://user-images.githubusercontent.com/53310247/150643122-6f077399-9a12-4982-9bd1-b75b504bfda6.png)

# Further Reading

* http://gurneyjourney.blogspot.com/2008/02/from-mask-to-palette.html
* https://mypaintingclub.com/blog/post/39-The-Gamut-Mask-Tool - the original page this tool is from. This video tells you how to use it
* [Gamut Mask Intro](https://vimeo.com/390100574?embedded=true&source=video_title&owner=12103469) - Linked video within that post
* [Gamut Masking](https://www.youtube.com/watch?v=qfE4E5goEIc) - Video demonstration of using a gamut mask in different ways 
* [Colour Harmony - 10 Minutes To Better Painting - Episode 5](https://www.youtube.com/watch?v=4LhcNbFMkTw) - doesn't specifically use the word "gamut" or use any masking but is a very similar concept, explaining why the center of the wheel heads towards gray.

# Terms of Use
Don't sell it. If you have money to throw you should consider signing up for some of Richard Robinson's courses at https://mypaintingclub.com/!

If you are Richard Robinson and you want me to take this down i will.
