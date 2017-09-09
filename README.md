# Messy Room!

Have you ever felt like your room was a maze? Well, let's imagine it! Recreate your room in Maya and let's import that into Unity to create a maze game!  

An Example of What Is Possible! 
![A Cool Example](https://orig05.deviantart.net/53fd/f/2010/057/c/d/cdc8e1f3aaa95c0d0808fcb81f2db6fc.jpg)

## Objective

Use **Maya Polygons** and tools to recreate your room. Import this asset into **Unity** and add **Prefabs**, **Script** and **Collision** components to create a maze game.

## Prerequisites

To complete this project, students should have the following:
* Basic understanding of Unity Interface.

## Your Challenge

### Part I

To complete Part I, fulfill the following requirements:
1. Follow along with the instructor to create a few objects in Maya.
2. Now, think about what objects are in your room. What shapes are they? Recreate as much as possible using the modeling tools!
3. Add materials (and colors) to your objects.

You should have at least 10 different objects in your scene.

Examples: Bed, desk, vase, window, door, books, video games...etc.

### Part II

To complete Part II, fulfill the following requirements:
1. Open up Unity.
2. Create a New Project called "Room Maze".
3. In the Project View, right click on Assets -> Import New Asset.
4. Find the file for the room you created in Maya.
5. Click on this scene when it appears in your Project View.
6. In the Inspector, check off the box ```Generate Colliders```.

### Part III

To complete Part III, fulfill the following requirements:
1. Create a Sphere by going to the GameObject Menu -> 3D Object -> Sphere
2. Position this sphere so that it is above the Room scene.
3. Click on the sphere.
4. In the Inspector, add a Rigidbody Component.

Resource: https://github.com/junior-devleague/marble-traveller/blob/master/part-2-controls/1-rigid-body.md

5. Add a New Script to this sphere that will allow it to roll on the floor.

Resource: https://github.com/junior-devleague/marble-traveller/blob/master/part-2-controls/2-moving-player.md

6. Have the camera follow the ball as it rolls.

Resource: https://github.com/junior-devleague/marble-traveller/tree/master/part-3-camera

7. Create collectible objects that the sphere can pick up as it rolls!

Resource: https://github.com/junior-devleague/marble-traveller/tree/master/part-4-collectibles

## Stretch Goals
1. How can we make our player jump? Add a jumping functionality with the spacebar! Hint: Research Input.GetKeyDown!
