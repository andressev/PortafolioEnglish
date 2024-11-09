
# Intro

Hi, my name is Andrés, I’m a student majoring in Applied Mathematics and Data Science at ITAM. I spend my time designing and experimenting with programs that produce interesting results.

I’m primarily interested in `interactive displays`, whether they are:

`Educational video games`

`Interesting structures`

`Augmented Reality`

I work with Unity and TouchDesigner. Below is my portfolio, featuring my most relevant projects and some techniques I’ve learned to implement them.

You can email me at **andressevilla81@gmail.com**

# Portfolio

## Meteorite 

I’m `currently working` on Meteorite:

A `spaceship` traveling at `high speed` through space, having to avoid asteroids and enemy ships.

**Meteorite3D**

![Meteorite3dClip](https://github.com/user-attachments/assets/ed9a4dc2-f446-4bbc-b045-c096f70cdfcb)

The `new version is in 3D`, but the idea originates from shoot 'em up games of the 80s-90s, with the `first` version being `a 2D version.`

**Meteorite2D**

![Meteorite2dClip](https://github.com/user-attachments/assets/e97e80de-63ea-46aa-be53-cf1baaf0f02a)

## Dive In

`A game inspired by diving.`

It’s about `learning about the ocean` and `the species` that live in it.

The player `explores a labyrinthine coral reef` searching for `animals` they can learn about. Each animal has `interesting facts` to share with the player if they are found.

![DiveINlvl2clip](https://github.com/user-attachments/assets/25ed037c-8543-4767-864e-97dca579d2ad)

**Don’t run out of oxygen!**

![DiveIN1](https://github.com/user-attachments/assets/edef0bae-5085-4f4d-a9eb-0eae193c81eb)

## GridSpace

**GridSpace Engine HLSL - UNITY**

[GridSpace](https://github.com/andressev/GridSpacee) is a cellular automata engine.

A `cellular automaton` is any `rule` applied individually to a group of pixels, at timed intervals. The rules usually involve `asking a pixel about its environment`: how many pixels are on within a radius of n? With this answer, you can tell the pixel to turn off, stay on, do nothing, etc.

The point is, there’s an `infinity of possible rules`, an infinity of possible environments. Each of these possible configurations we call `states`. States are generally `quite chaotic`, but every so often they organize to create something that resembles cellular life.

The purpose of GridSpace is to `share a piece of this infinite space with its users` and facilitate the journey through all these states. [Here](https://github.com/andressev/GridSpacee) you can download GridSpace.

**The user initially creates a neighborhood environment to apply rules.**

![GifNeighborhoods](https://github.com/user-attachments/assets/50d62360-fe90-4d12-9d1b-b9752f77f903)

**Then chooses up to 4 environments/neighborhoods.**

![GifNHpicker](https://github.com/user-attachments/assets/5dcbd464-9484-418f-a433-c6ba10b94331)

Afterwards, the user can mutate the rules using the controls to find the most interesting states.

**Mutation mode**

![GridSpace Portfolio](https://github.com/user-attachments/assets/15eea6ea-17d4-42ae-805a-d90a68d3d044)

The user can `travel comfortably` `through cell mutations`. Across all of GridSpace, there are `10^308 possible states`; the number of atoms in the universe is around 10^80.

[Mutation Mode Gameplay Video](https://www.youtube.com/watch?v=BqFUAaOdQgY)

## Pointcloud Experiments

**Physically accurate gravity in TouchDesigner GLSL**

This project stems from an attempt to `accurately represent gravity` in space; it’s not actually a force. Rather, `a gravitational field literally bends space`.

The white lines represent the three-dimensional space we inhabit, and they are contracted by the object in the center. The `closer they get to the gravitational center`, `or depending on the amount of mass at the center`, the more they contract.

https://github.com/user-attachments/assets/5176f8b3-8e50-479f-a63c-6b3ed25c5d67

The lines are made of about 200,000 points in total. A gradual transformation is applied to each point to `replicate the effect of gravity on the fabric of space`.

**Spherical Gravity**

If, in addition to `transforming` to emulate gravity, we also applied a transformation to the `angles with respect to the origin`, we get a result that no longer adheres to reality but is visually appealing.

https://github.com/user-attachments/assets/4e5555e4-b39c-4b27-b432-19360064908a

## Mandelbrot

**Mandelbrot 2D GLSL-TouchDesigner**

This project is a `tool to explore` the famous `Mandelbrot set`. Later, I made the fractal `audio-reactive.`

**Sound On**

https://github.com/user-attachments/assets/45790cdb-8b24-425b-8f4a-bef6a2e42f66

**Mandelbrot 3D Raymarched**

I also learned a bit about `raymarching`, a technique for projecting and creating three-dimensional shapes on a plane using distance functions. I `found a function` for a `3D version of Mandelbrot`, and with TouchDesigner and some lighting tricks, this was the result.

https://github.com/user-attachments/assets/5d88fa54-8d69-4e60-a4db-23ef1f518690
