# UE4 Labs for Game Development course

## Printscreens

MP2 (Lean) - Airplane tower watch invites for leaning

<img src="https://user-images.githubusercontent.com/72025352/155263745-9b748489-ccc5-4558-b333-18b7f9e67b2d.PNG" width="500"/>


MP2 (Dodge) - Big train forces player to dodge

<img src="https://user-images.githubusercontent.com/72025352/155263747-e9fd14da-3350-4c8d-94e8-68e17f428740.PNG" width="500"/>

MP2 (Left & Right) - Hang glide in space that tries to evade asteroids

<img src="https://user-images.githubusercontent.com/72025352/155263749-ecaabd64-963c-4cfe-b7c0-b03ae25efc85.PNG" width="500"/>

MP3 - Spawn boxes, drag paint buckets to color boxes. Arrange buckets to create unique designs.

<img src="https://user-images.githubusercontent.com/72025352/155263738-7290985c-ea36-4503-9ad1-1ff17da215a5.PNG" width="500"/>


## Mini Project 3
### Focus: Blueprint Communication

[Folder](./Content/Lessons/Lesson3/miniProject3)

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

