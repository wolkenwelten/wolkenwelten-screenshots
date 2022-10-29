# WolkenWelten Screenshots
Here you can see current (and old) screenshots of the Rust WolkenWelten rewrite.

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
