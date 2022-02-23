## Description
This is a painting sandbox game.
Press the moving '+1' button to spawn new blocks.
Move the block around by drag-and-drop.

In the sky, buckets of paint will spawn, left-click on them for a color sphere to spawn.
This color sphere can be moved around with drag-and-drop.
When a sphere comes in contact with a block, it paints the block with the sphere's color.

Spawn blocks and move them around. Build something nice!
Use the color spheres to paint the blocks to create something unique.



Interactable actors:
* Cubes (Drag-N-Drop w/ left click)
* Button to spawn cubes (Left click)
* Paint buckets to spawn color spheres (Left click)
* Color spheres (Drag-N-Drop w/ left click)

Sequence:
* The spawning point for new paint buckets are constantly on the move, as designed with a sequence.
* The '+1' button is moving left-to-right, which was achieved with a sequence.

Timelines:
* When color spheres are left on the ground, they will start jumping, this is accomplished with a timeline.
* The paint buckets shift color; this was implemented with timelines (for each R,G,B) as well.