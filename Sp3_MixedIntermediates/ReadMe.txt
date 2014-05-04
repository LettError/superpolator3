Mixed_intermediates.sp3
May 4 2014, version 1.0

This designspace shows how Superpolator3 can handle master placement. The masters contain 4 glyphs, A, D, E, F, each with a different setup.

A:	master in the Light and the Black, no master in the Medium
This is effectively a single linear interpolation between the Light and the Black. The glyph is missing in the Medium master.

D: 	only a master in the black, nowhere else.
The Black is the only glyph present in this designspace. Therefor there is no other data to interpolate with, so the black shape is the only one visible at any designspace location.

E:	masters in Light, Medium and Black, Medium is the intermediate.
This results in a Thin to Medium interpolation, and then a Medium to Black interpolation. When dragging the break is clearly visible.

F:	same as E, but the Medium master glyph is muted.
Even with a master glyph in the Medium, it is muted so it does not have an effect in the designspace. This means that the interpolation runs from the Light to the Black. Do a comparison with the E and you will note the effects on the thins of the shape. 

All rights reserved, LettError.
Superpolator is a registered trademark. 
Superpolator.com.