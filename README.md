# WolkenWelten Screenshots
Here you can see current (and old) screenshots of the Rust WolkenWelten rewrite.

### 2022-11-13 - Added some variety
![A fancy tree](./2022_11_13.jpg)
Fixed a couple of graphical glitches, and apart from that added 2 new tree models.

### 2022-11-12 - Fancy trees
![A fancy tree](./2022_11_12.jpg)
Added functionality so that .vox assets can be used during worldgen, tried it out
with a tree I modeled in goxel in a couple minutes, so far everything looks very
promising. Might look into adding distortiong filters to add a bit of variance.

### 2022-11-11 - (Better) Landscapes
![Mountains](./2022_11_11.jpg)
Improved the landscape generator a bit, mainly less artifacts and nicer mountains.

### 2022-11-10 - Landscapes
![Mountains](./2022_11_10.jpg)
Played around with the `noise` crate and made a (hopefully) slightly more appealing
world generator.

### 2022-11-06 - Healthbar
![Hearts](./2022_11_06.jpg)
Got around to building a crude health system and UI to show the current player's health, next up:
fall damage.

### 2022-11-04 - Voxel meshes
![Explosive particles](./2022_11_04.jpg)
And now we can import voxel meshes from .vox files that can be created with tools such as
goxel. Since we are using the same meshgen function that's doing the world we get ambient occlusion
as well.

### 2022-11-03 - Particles
![Explosive particles](./2022_11_03.jpg)
Finally got around to adding a simple particle system so the exploding pears look less
off. The effect of course looks slightly nicer animated :)

### 2022-10-29 - Dynamic world
![Dynamic world](./2022_10_29.jpg)
Now we automatically recalculate lightmaps/meshes as the underlying voxel
data changes. In order to test this out the pears now explode on contact, leaving
behind a nice crater.

### 2022-10-26 - Ambient occlusion
![Ambient occlusion](./2022_10_26_ao.jpg)
Figured out why ambient occlusion wasn't working before, now things look much
nicer.

### 2022-10-26 - Smooth lighting
![Smooth shading](./2022_10_26.jpg)
Still very much a prototype, but we're getting there, the lightmap calculation is
still incorrect quite often since it doesn't look at neighboring chunks yet.

### 2022-10-25 - Flat shading
![Flat shading](./2022_10_25.png)
Got flat shading to work, although there currently are no lightmaps, so I'm using
a XOR test pattern for now.

### 2022-10-25 - Beginnings
![Beginnings](./2022_10_24.png)
The state of the rewrite 2 weeks in, quite content with the overall progress,
still looks quite bad, but a lot of optimizations are already included in the voxel
renderer.
