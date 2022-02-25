# Unreal Engine 4 - Labs for Game Development course at NUS
This is my personal repository for the different labs I have created during the module `CS3247 Game Development` at National University of Singapore during the second semester of AY21/22. For full descriptions of the labs' objectives, see https://varlabs.comp.nus.edu.sg/tutorial/index.html.

# Mini Project 5
### Focus: Physics

## Description

The theme for this game will become apparent as you play it.

**"Out of sight, out of mind."**

This is a basketball game unlike most. In this game, the player runs around and tries to score points by shooting the ball through the hoop. To make things harder, there are enemies that the player needs to keep away from. 

As soon as an enemy comes into the player's vision, it will start moving towards the player. Hence, the player need to think about where to look while at the same time trying to score points.

<img src="https://user-images.githubusercontent.com/72025352/155761156-18669992-7db6-4217-873f-67a541e994d7.PNG" width="500"/>

## Controls

- `WASD` x Move around.

- `Left click` x Pick up the ball. Can also be used to drop the ball.

- `Right click` x Launch the ball. When holding a ball, an arrow indicates where the player is aiming. Additionally, in the top of the HUD, a power bar displays the current power that's going to be used for the shot. Use it to plan the shot in order to score points.



# Mini Project 3
### Focus: Blueprint Communication

[`Folder`](./Content/Lessons/Lesson3/miniProject3)

## Description
This is a painting sandbox game.
Press the moving '+1' button to spawn new blocks.
Move the block around by drag-and-drop.

In the sky, buckets of paint will spawn, left-click on them for a color sphere to spawn.
This color sphere can be moved around with drag-and-drop.
When a sphere comes in contact with a block, it paints the block with the sphere's color.

Spawn blocks and move them around. Build something nice!
Use the color spheres to paint the blocks to create something unique.

<img src="https://user-images.githubusercontent.com/72025352/155263738-7290985c-ea36-4503-9ad1-1ff17da215a5.PNG" width="500"/>

## Notable features
### Interactable actors
* Cubes (Drag-N-Drop w/ left click)
* Button to spawn cubes (Left click)
* Paint buckets to spawn color spheres (Left click)
* Color spheres (Drag-N-Drop w/ left click)

### Sequence
* The spawning point for new paint buckets are constantly on the move, as designed with a sequence.
* The '+1' button is moving left-to-right, which was achieved with a sequence.

### Timelines
* When color spheres are left on the ground, they will start jumping, this is accomplished with a timeline.
* The paint buckets shift color; this was implemented with timelines (for each R,G,B) as well.



# Mini Project 2
### Focus: VR Scripting

[`Folder`](./Content/Lessons/Lesson3/miniProject3)

## Description

### Lean
**Objective**. Inspire the viewer to lean in for better perspective.

**Description**. The player is positioned in Air Traffic Control Tower and manages an airport. In order to improve the player's view, the player may lean in to get another perspective and follow the plane better. 

<img src="https://user-images.githubusercontent.com/72025352/155263745-9b748489-ccc5-4558-b333-18b7f9e67b2d.PNG" width="500"/>


### Dodge - Big train forces player to dodge
**Objective**. Inspire the viewer to dip, dodge, duck, dive, and/or dodge.

**Description**. The player is stuck in a Railway Track and cannot move. A train cart is approaching and as it gets closer to the player, it slams it breaks and tries to stop before hitting the player. Thankfully the train cart is large and the player can dodge to fit underneath the cart and avoid collision.

<img src="https://user-images.githubusercontent.com/72025352/155263747-e9fd14da-3350-4c8d-94e8-68e17f428740.PNG" width="500"/>


### Left & Right
**Objective**. Inspire the user to look left/right or up/down repeatedly.

**Description**. The player is casually flying a hang glider in space. There is no possibility of steering the glider, but the nearby asteroids are in orbit and may sometimes hit the player who looks around to hopefully evade the next asteroid hit.


<img src="https://user-images.githubusercontent.com/72025352/155263749-ecaabd64-963c-4cfe-b7c0-b03ae25efc85.PNG" width="500"/>

