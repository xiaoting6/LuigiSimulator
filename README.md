# LuigiSimulator
A 3D Simulation of our 2015 VEX Skyrise Robot, Luigi. Created using Unity Game Engine, Blender, and Autodesk Inventor.

## Demo Video

[![Simulator Demo](http://img.youtube.com/vi/s_RUZVgpZfw/0.jpg)](http://www.youtube.com/watch?v=s_RUZVgpZfw)

## Overview

I made this simulator for the 2015 VEX National competition in Council Bluffs, Iowa. It is a simulator of Team 2360N's robot, dubbed "Luigi."

The simulator was designed to be controlled using two Xbox 360 controllers, similar to how Luigi was actually controlled on the field with two VEX controllers. The controls in the simulator work identically to the controls of the real robot.

## The Robot

This is Luigi. He is pleased to meet you.

<img src="http://i.imgur.com/G0jQd7v.jpg" width="200"> <img src="http://i.imgur.com/5DJb3k1.jpg" width="200"> <img src="http://i.imgur.com/1NW5x03.jpg" width="200"> 

<img src="http://i.imgur.com/l7hxam4.jpg" width="200"> <img src="http://i.imgur.com/p1FfoIs.jpg" width="200"> <img src="http://i.imgur.com/aAVsDVF.jpg" width="200">



## Modeling the Robot

To create the model of the robot, I took *many* reference pictures of it and created a very rough model of the bot in Autodesk Inventor. 

<img src="http://i.imgur.com/944g6OA.png" width="200"> <img src="http://i.imgur.com/QyqOb6q.png" width="200"> <img src="http://i.imgur.com/7U5WqDk.png" width="200">

I exported the Inventor model to an STL file and imported it into Blender because, for SOME REASON, Autodesk likes to export files with MILLIONS of vertices!! Not very good for a 30 fps robot simulator...

<p align="center">
  <img src="http://i.imgur.com/sdQqfC0.png" width="300"/>
</p>

So I had to meticulously remodel the whole robot in Blender using basic polygons in order to reduce the vertex count. That was... fun...

<img src="http://i.imgur.com/9Fa1bty.png" width="200"> <img src="http://i.imgur.com/yJwj83T.png" width="200"> <img src="http://i.imgur.com/k27wcuT.png" width="200"> <img src="http://i.imgur.com/A5K3BxO.png" width="200">

<img src="http://i.imgur.com/pdMr7aq.png" width="200"> <img src="http://i.imgur.com/YwNAbA0.png" width="200"> <img src="" width="200"> <img src="" width="200">

Once I had remodeled the bot, I performed the same process for the game field, the skyrise pins, and the cubes. I imported all of the Blender assets into Unity and began programming the simulator.
