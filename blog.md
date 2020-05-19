# A guide to understanding Perlin Noise

## What it is and why it's useful

(Start with a picture.)

* Use it for colouring things in.
* Use it for making lumpy things - hills, mountains, textured surfaces.

* Continuous and smooth.
* No obvious grain/grid/direction to it. Looks natural and organic, not man-made or crystalline.
* All the features (blobs) are about the same size.
* Can be generated on-demand. (Needs elaboration, examples. Maybe Minecraft?)
* Looks random. Again, natural and organic.

## The big idea - combining gradients

(Maybe start with value noise and develop to Perlin.)

## The algorithm at a high level

* Assign gradient vectors to grid points
* Colour vertex neighbourhoods with gradients
* Fill in smoothly between vertices ("interpolation"!)

## Let's implement it