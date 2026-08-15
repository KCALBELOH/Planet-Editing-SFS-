# Planet-Editing SFS
(Probably means uncertain)

This is how to edit planets in sfs and stats explained :

Go to SFS files (Spaceflight simulator - Spaceflight simulator game - spaceflight simulator data - custom solar systems - Solar System Name),

Addiionally :

Copy example folder,
In (Solar System Name), there will be texture data (For planet ground textures), Heightmaps (Where the heightmaps are), Import_data (includes creator name, version which doesnt relate to game version, description), Space_Center data (Address means where it planet it is. Angle means how tilted it is, 90 is 90 degrees, normal value. horizontalposition is where horizontally the space center is, 365 means it will be in 90 degree relative to planet. height means what height it will be, in meters)

Version : The game version it uses.

Radius : Its radius, in meters, radiusdifficultyscale : its radius in different gamemodes such as hard, or realitic.

Gravity : Its gravity, in m/s2, 9.8 is same to earths, gravitydifficultyscale : its gravity in gamemodes like hard or realistic.

Timewarp height : Where can you timewarp (non physics timewarp) before locked out of non physics timewarp and going to physics timewarp.

velocityarrowsheight (probably) : Where the arrow during below the timewarp height is?

mapcolor : In RGB, what the planets color looks in mapview, must be above 0 and below 1, A (Alpha) : Transperancy, must be above 0 and below 1.

significant : if true, in map view it appears, if false, in map view, it only appears when you get close to it.

rotatecamera: if true, your camera will rotate along the ground, if false, it wont.

(ATMOSPHERE_PHYSICS_DATA) -

height : How high the physics of the atmosphere goes before its gone.

density : How dense the atmosphere is, 0.005 is same to earth, in psi? bar? i dont know.

curve : How smoothly it will transform from the upper to lower atmosphere.

curvescale (probably) : Same as curve, but how it will be in hard, or realistic gamemode.

parachutemultiplier : 1 means parachute can be deployed (non-fully) at 2500m, fully at 500m.

upperatmosphere : In percent above , how much the upper atmosphere is.




