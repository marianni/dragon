# Physical based animations and mathematical modelling 2018

<img src="Fantasy-dragon-wallpaper.jpg" alt="Dragon" height="500" width="1000">

# Authors

Marianna Ráchelová

Martina Bodišová

# About

Create animation of a dragon floating above the huge medieval castle. Show the dragon moving its
wings and spitting the fire. Show growing fire, show large fire, show smaller fire. Create a little story.

# Storyboard

![Dragon](http://marianni.github.io/dragon/storyboard.jpg)

# Diary

| Date                    | Progress                                                                           | 
|:------------------------|:-----------------------------------------------------------------------------------|
| 15/10/2018              | Finished storyboard                                                                | 
| 15/10/2018 - 31/10/2018 | Looking for dragon model and learning Blender                                      | 
| 01/11/2018 - 15/11/2018 | Creating grass with particle system , adding wind and model of castle              |
| 16/11/2018 - 29/11/2018 | Creating model of dragon egg, breaking egg animation                               |
| 30/11/2018 - 16/12/2018 | Flying dragon animation, align camera to spline path                               |
| 16/12/2018              | Creating of rain effect using particle system. Last edits,creating demo            |
| 02/01/2019 - 09/01/2019 | Improving of rain effect, creating model of rain drop.Improving of dragon's flight.|
| 10/01/2019 - 17/01/2019 | Creating animation of dragon spitting the fire.                                    |
| 18/01/2019 - 27/01/2019 | Last edits, rendering of animations, creating video.                               |


# Used effects

## Rendering

1. Quality texture on objects
2. Good gloss on surface

## Audio

3. 

## Motion

4. Object's motion after the spline 
5. Camera motion after the spline
6. Sun motion after the spline
7. Dragon flight
8. Dragon walk

## Physically natural effects

9. Rain 
10. Wind
11. Collision liquid and object 
12. Grass with hair

## Physical objects

13. Model of dragon egg
14. Model of rain drop
15. Collision of objects

# Creating of scenes

## Dragon egg view

We used the model of the castle from internet. Link available here <a href="https://free3d.com/3d-model/fantasy-castle-40715.html">Castle model</a>.
<br>
We created simple model of dragon egg. We tried to use the cell fraction to break the egg. Cell fraction is special add on using to break the object's surface. This add on use the Woronoi algorithm for breaking surface as well. Unfortunately this add on is using Blender game engine and this kind of add on is incompatible with Particle system. Engine is used for rendering. We decided to not include dragon egg cracking surface in final animation. 
<br>
Next we created green grass using Particle system. First we added new mesh - plane. To this plane we add modifier particle system. We set up some properties like type of material - dirt and grass, type of particle system - hair, hair-length etc.
On the grass we can see the wind is blowing.
<br>
<br>
<a href="https://www.youtube.com/watch?v=rJGbwv8OGSw&feature=youtu.be">Dragon egg view</a>

# Images

<img src="scena_1.png" alt="scena_1" height="500" width="1000">
<br>
<img src="scena_2.png" alt="scena_2" height="500" width="1000">
<br>

# Demos

<a href="https://www.youtube.com/watch?v=bYImpFTVHck&feature=youtu.be">Dragon fly</a>


<a href="https://www.youtube.com/watch?v=Ii3bCEb9IdM&feature=youtu.be">Castle</a>

# S3 theme

<a href="S3.pdf" download="S3">S3</a>
